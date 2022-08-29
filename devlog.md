# Setup

1. Install nvm and switch to node v16.
2. Create npm repo using `npm init`
3. Install webpack and webpack cli using `npm install webpack webpack-cli --save-dev`
4. Create index.html and src/index.js files.
5. Follow https://webpack.js.org/guides/getting-started/.
6. Install babel, `npm install --save-dev babel-loader @babel/core`
7. Install preset-env, `npm install @babel/preset-env --save-dev`
8. Create test-plugin.js file in plugin directory.
9. Setup webpack inside plugin directory to enable bundling.
10. After struggling with the config to output the default function, I figured out that I have to specify a library name!
11. Still another error now in the parent project, `self is not defined`.