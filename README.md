## This repository includes: API of the engine and examples of plugins.

# Tutorial
1.`dotnet new classlib`
2.Copy the engine library to the project folder.
3.Link the engine library and your plugin.
4. 
Implement the Engine Plugin interface in the main class of your plugin.
```csharp
using System;
using MantisEngine.Engine.Modules.Scripting.Plugin;

namespace example_plugin
{
    public class Plugin : EnginePlugin
    {
        public string Name => "Example plugin";

        public string Description => "plugin description";

        public string Version => "plugin_version";
        public string Author => "plugin author";

        public void MainFunction()
        {
            //Plugin main function code



            //
        }
    }
}

```
