Below are the steps to get your plugin running. You can also find instructions at:

https://www.figma.com/plugin-docs/plugin-quickstart-guide/

Get the latest type definitions for the plugin API by running:

> npm install --save-dev @figma/plugin-typings

To launch:

> npm install (to install npm dependencies)
> npm run build (to build TS file to JS)
> Hit Ctrl-Shift-B in Windows, or Command-Shift-B for Mac.
> Select watch-tsconfig.json (compiles ts to js and updates anytime there's a change)
