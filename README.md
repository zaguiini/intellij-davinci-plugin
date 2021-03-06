# com.zaguiini.davinci

[Davinci](https://www.npmjs.com/package/@toptal/davinci) tools, now on Intellij suite!

## Installation

Grab the [distribution package](#bundling-process) and go to `Plugins > Install from disk` then select it.

## Usage

Right click on any module and select `New > ...` to create a `Page` or a `Component`, entering the desired name.
You can also right click the `modules` folder to create a new module.

## Development

Open this project inside Intellij IDEA and then run the plugin as you normally would.
Check `build.gradle`'s `runIde` block to change the test IDE.

## Bundling process

Run the `buildPlugin` Gradle task, and the zip should be located at `build/distributions/Davinci.zip`

## TODO

### Component suggestion

As soon as the users instantiates an element that doesn't resolve to any reference inside the file, suggest the creation of the given component, inferring as many props as possible, in the nearest `components` folder.

### More commands

For now, this plugin only creates modules, components and pages, but Davinci provides much more!

### Keyboard interaction

Be able to run the features of this plugin right from the keyboard would be better -- ergonomically speaking :)

## License

MIT
