# My Editorconfig

<a href="https://editorconfig.org"><img src="https://raw.githubusercontent.com/editorconfig/editorconfig/master/assets/EditorConfig_Logo.svg" alt="Editorconfig icon" width="150" height="150" /></a>

My preferred [Editorconfig](https://editorconfig.org) which i use between my projects.

I recommend using this config with [my Prettier config](https://github.com/socnik/my-prettier-config). They are fully compatible between themselves.

This config is in the [`.editorconfig`](https://github.com/socnik/my-editorconfig/tree/main/.editorconfig) file.

## Usage

### Stage 0

Download Editorconfig template to your project with [`degit`](https://github.com/Rich-Harris/degit):

```shell
npx degit socnik/my-editorconfig/.editorconfig
```

### Stage 1

Install [VSCode extension](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) for Editorconfig integration.

### Stage 2a _(optional)_

Add Editorconfig VSCode extension to workspace recommendations:

```jsonc
// .vscode/extensions.json

{
  "recommendations": [
    // ...
    "editorconfig.editorconfig",
    // ...
  ],
}
```

### Stage 2b _(optional)_

Add Editorconfig VSCode extension to your [`Devcontainer`](https://code.visualstudio.com/docs/devcontainers/containers):

```jsonc
// .devcontainer/devcontainer.json

{
  // ...
  "customizations": {
    // ...
    "vscode": {
      "extensions": [
        // ...
        "editorconfig.editorconfig",
        // ...
      ],
    },
    // ...
  },
  // ...
}
```

### Stage 3

**All ready!**
