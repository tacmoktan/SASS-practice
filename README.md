# SASS
* Syntactically Awesome Style Sheets
* CSS preprocessor
* CSS on steroids :laughing:

## Topics
1. Variables
    * begins with `$` symbol.
    * [example](styles/scss/_variables.scss)

2. Nesting styles
    * [example](styles/styles.scss)

3. Mixins  
    * Reusable block of css code.
    * begins with `mixin` keyword.
    * [example](styles/scss/_mixins.scss)

4. Include and Import
    * `@include <mixin_name>` and `@import '<path_to_the_file>'`
    * [example](styles/styles.scss)

5. Pseudo Classes
    * [example](styles/styles.scss) : `:before`, `:after`, `:hover`,etc.

6. Mathematical operators
    * [example](styles/styles.scss) : `max-width:(80%/3)`

7. Built-in functions
    * [source](https://sass-lang.com/documentation/functions)
    * [example](styles/styles.scss) : `lighten`, `darken`, `complement`(*color functions*) etc.

8. The `@content` keyword
    * Used for responsive layout.
    * [example](styles/scss/_mixins.scss)