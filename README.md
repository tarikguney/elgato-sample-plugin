
# SetTitle Plugin

Based on the following image:

`NumberDisplay` is a sample plugin demonstrating the [Stream Deck SDK](https://developer.elgato.com/documentation/stream-deck/).

I (@tarikguney) modified this sample code to learn how to develop a plugin for Elgato Stream Deck. 

You can find the new source code under `Sources/com.tarikguney.settitle.sdPlugin`

You can also find the `DistributionTool.exe` under `Sources` folder. If you want to build a `.streamDeckPlugin` compiled file, go ahead and run the following command:

```
DistributionTool.exe -b -i com.tarikguney.settitle.sdPlugin -o .
```

And then, double click on the generated file, which will automatically install the plugin to your Stream Deck application under `Custom Plugins` category.

Enjoy!

Made by @tarikguney in Salt Lake City, 2019.