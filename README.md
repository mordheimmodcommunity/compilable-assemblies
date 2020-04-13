# WORK IN PROGRESS

## dependencies

recommended IDE: VSCode https://code.visualstudio.com/

.NET core sdk 2.1 https://dotnet.microsoft.com/download/dotnet-core/2.1
.NET core sdk 3.1 https://dotnet.microsoft.com/download/dotnet-core/3.1
.NET Framework 3.5

TODO: automate .netcore install with this https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-install-script

# auto install of .NET Framework 3.5 for compilation

powershell as admin
`Enable-WindowsOptionalFeature -Online -NoRestart -FeatureName "NetFx3"`

Required computer restart

# asset decompilation

probably some java sdk ( for assets ) use curl for installing ?
https://github.com/ata4/disunity

# CI

formatter: https://github.com/dotnet/format

run ./install