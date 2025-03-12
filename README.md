# devlab.buildingblocks.dotnet

## Como usar

Adicione o repositório do GitHub Packages ao seu `NuGet.config`:

```xml
<configuration>
  <packageSources>
    <add key="github" value="https://nuget.pkg.github.com/pedrobarao/index.json" />
  </packageSources>
</configuration>
```

Adicione o pacote ao seu projeto:

```bash
dotnet add package DevLab.Core --version 1.0.0
```