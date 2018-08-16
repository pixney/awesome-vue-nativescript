## Installation
[Documentation](https://nativescript-vue.org/en/docs/getting-started/installation/)


## Quick Start
[Quick Start](https://nativescript-vue.org/en/docs/getting-started/quick-start/)

## Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli/tree/master).

``` bash
# Scaffold project
npm install -g @vue/cli @vue/cli-init
vue init nativescript-vue/vue-cli-template#next <project-name>
cd <project-name>

# Install dependencies
npm install

# Build for production
tns build <platform> --bundle

# Build, watch for changes and debug the application
tns debug <platform> --bundle

# Build, watch for changes and run the application
tns run <platform> --bundle

# Clean the NativeScript application instance
tns platform remove <platform>
```

## Using NativeScript plugins

Installing plugins is the same as official NativeScript [documentation](https://docs.nativescript.org/plugins/plugins#installing-plugins).

Use `tns plugin add` from the root of the project directory.

```shell
tns plugin add <plugin-name>
```


`npm install -g @vue/cli`  

Also `unsetopt nomatch` in `~/.zshrc` to disable it

https://github.com/nativescript-vue/vue-cli-template/tree/next

Some comments regarding the lifecycle.  
https://github.com/nativescript-vue/nativescript-vue.org/issues/177
