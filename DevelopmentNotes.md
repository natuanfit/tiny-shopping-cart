# 1. Tools
 - Visual Studio Code (latest version) with the following extensions:
    + The C# extension is powered by OmniSharp.

 - GIT

 - NodeJS
    + npm
        * Yeoman scaffolding system: First thing is to install yo using npm: npm install -g yo
            + Yeoman generator for ASP.NET Core projects - generator-aspnet: npm install -g generator-aspnet
    + bower
    + gulp

# 2. Project Structure
 - Presentation layer
    + ASP.NET MVC Core project

# 3. Steps by Steps to create solution
# 3.1 Set up developement environment
 - Step 1: Install Visual Studio Code
 - Step 2: Install .NET Core SDK which depends on which OS you're running: https://www.microsoft.com/net/core#windows
 - Step 3: Install some extensions for Visual Studio Code using command palette:
    + The C# extension is powered by OmniSharp: coding C#
    + Spelling and Grammar Checker: check spelling and grammar that can support for a lot of file types.
 - Step 4: Install NodeJS & npm. Please refer the URL: https://nodejs.org/en/
 - Step 5: Install Yeoman. This is a scaffolding system which help us to create solution quickly.
 - Step 6: Install Yeoman generator named generator-aspnet
 - Step 7: Create a web application (ASP.NET MVC CORE) named TinyShoppingCart.WebApp by using Yeoman generator: yo aspnet (choosing An Empty Application template)
 - Step 8: Restore .NET packages for the web application project: dotnet Restore
 - Step 9: Try to build and run the web application: dotnet build and dotnet run
 - Step 10: Try to debug the web application with Visual Studio Code (2 files: launch.json and tasks.json will be created under .vscode directory). Please refer to: https://wannabeegeek.com/2016/06/23/debugging-dotnet-apps-using-vs-code-on-mac/
 - Step 11: Using ASP.NET MVC Core middleware by configuring dependencies to MVC on project.json file
 - Step 12: Manually create Models, Views and Controllers folders under the project TinyShoppingCart.WebApp
 - Step 13: Try to create a new controller named HomeController by using yo aspnet:mvccontroller HomeController.cs
 - Step 14: Try to create a a view named Index.cshtml by using yo asp.net:mvcview Index


