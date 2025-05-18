# mpc-quickstatrt-client
Client based on Model Context Protocol. 

# To create a new client
## Create new project
dotnet new console -n QuickstartClient

## Import dependencies
dotnet add package ModelContextProtocol --prerelease

dotnet add package Anthropic.SDK

dotnet add package Microsoft.Extensions.Hosting

## Setting up API Key

dotnet user-secrets init

dotnet user-secrets set "ANTHROPIC_API_KEY" "<your key here>"

## Add code using MPC SDKs and Microsoft libraries

.\Program.cs 

## Compile and run
dotnet run -- path/to/server.csproj # dotnet server
