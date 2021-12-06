## dotnet core application creation steps
* dotnet  (need to install dotnet sdk)
* *'dotnet new sln -o Helloworld'*
* cd Helloworld/
* *'dotnet new mvc -n Vamshi.Web'*
* *'dotnet sln add Vamshi.Web/Vamshi.Web.csproj'*
* *'dotnet build'* (by default it will come with debug mode, we can mention configuration as release like below)
* *'dotnet build --configuration release'* (the output is .dll files)
* cd Vamshi.Web/
* *'dotnet bin/Debug/net5.0/Vamshi.Web.dll'*
* *'dotnet publish -o /out'*  (it will generate outfolder and publish the only artifacts at the same location)
