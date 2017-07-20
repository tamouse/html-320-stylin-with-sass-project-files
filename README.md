# Using a single CSS file

Using the Sass `@import` feature, combine the `reset.scss` file in
with the `styles.scss` file.

1. convert `reset.scss` into a partial by putting an underscore at the beginning of the file name: `_reset.scss`.
2. edit `styles.scss` and import the reset partial at the beginning of
   the file: `@import "reset";` You don't put the underscore at the beginning of the file in the `@import` statement, and you don't put the extension, `.scss` either
3. Change `index.html` to remove the `reset.css` stylesheet link.
