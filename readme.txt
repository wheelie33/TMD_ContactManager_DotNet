Download and install dotnet SDK/CLI
https://www.microsoft.com/net/download/windows

cd into the directory you want to work from.

git clone https://github.com/wheelie33/TMD_ContactManager_DotNet .
(note the trailing period)

dotnet restore
dotnet build
dotnet test ContactManager_Tests
