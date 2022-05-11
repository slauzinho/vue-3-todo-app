# My Todos

Our plan is to create an application that let us manage a list of todos.

I should be able to:

- Add a todo
- Remove a todo
- Mark a todo as done

There is no strict design rule but if you want some insperation you can use this one:

<img src="https://cleanshot-cloud-fra.s3.eu-central-1.amazonaws.com/media/36216/sl3dxLo17vhR46he0mKGzHen73pvPFguII0G8Eis.jpeg?X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFkaDGV1LWNlbnRyYWwtMSJGMEQCIGnEcPFZNIuPnAEqBoV48fSGRGOeulSByQS%2BW2XcrVEzAiBnLVS%2BLCWOpYfUSsXae8bA5ZbCoGoYosmY%2BszK8Z7%2F7iqhAggyEAAaDDkxOTUxNDQ5MTY3NCIM6UZwfUEGfqtHAg3PKv4BGNM1WUOr9ufRPYJMATpEVNR8kPtHe5plBQ978ThYuibgD2rLUrO8LNsAC2i%2FEqzDUyG7BnNrYH9orNmgdXdPMhIHAEiM8oV9pgZf3rriEn9%2Bb0NuTtTKR6AyqC%2FJsnUVkpj%2BUQ%2FSrTkDvpHTd4VzOdBvD7n%2FIXLMdf79Dm6egRSwzPLN1eluDsTT5LTasPzASeD5H4l8hI7ejl%2B0iHK0eZmgjZ%2Fk%2BPcVxxe5co0NgRZcsX%2BWm%2F5DHCJOw3BaV7gzFVUc1KKAoXPbQiO7FNtvExeuASUKU0Y%2BYYNg%2FGMFFFfoDpA9AOmhdlpV8ZDKun%2BfhhrxAu8FN0LHDpb5u80wptXvkwY6mwGjJOTDBvzBgCdWKWt44Igufn4J1IIjV2LvM1NQ1mf66gea0c5SdLPZNwjGbklilsmdblc8nxNXmIPF%2BGYnPXRiFKhke%2FW75V44ElfJH9hriu%2F8WyXvMnfT3j8ijW82hS9i2atWrA3gD9qrBG%2Bc%2Bj2%2BDOwxKZcO4DuB4%2FawjBud73fFH0nNDp%2BWMyNPy28BzDARuFiwR3P8G4OtYQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=ASIA5MF2VVMNLSTR4WGI%2F20220511%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220511T181841Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Signature=ed73907098786e1d56c262b89ab362f4fe8ede76c6f85167599d3683630a6c7f" alt="photo" width="500"/>

## Vue 3

Since we are using Vue 3 we should use adopt the new [composition API](https://vuejs.org/guide/extras/composition-api-faq.html).

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VS Code's command palette, look for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default, Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VS Code window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).
