# Workshop-Web MVC-Core
Sample .NET Core 1.11 Application that is ready to push into Pivotal Cloud Foundry for Workshop purposes.

The only change to this template code was to add the code to read in the port parameter from the command line in Program.cs

To push into PCF:
  1. Publish Code using Visual Studio
  2. Navigate to the folder where the code was published
  3. Run 'cf push <appname> -b dotnet_core_buildpack
