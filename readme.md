# Topten.UIAutomation

Topten.UIAutomation is a nuget package that includes references for UIAutomationClient,
UIAutomationProvider and UIAutomationTypes for netcoreapp3.1 and net framework projects.

* For .NET Framework it adds framework references for these assemblies

* For netcoreapp3.1 it includes the required assemblies from Microsoft.WindowsDesktop.App plus a minimal set of dependencies so they can be used in non-WPF based applications.

Unfortunately, for netcoreapp3.1 there's a dependency on PresentationNative_cor3.dll which would
be nice to get rid of, but seems to be required.

Obviously this package is only useful to windows apps.

```
<ItemGroup>
    <PackageReference Include="Topten.UIAutomation" Version="0.0.1" />
</ItemGroup>
```


