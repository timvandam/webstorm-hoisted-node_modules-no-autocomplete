Setup:
1. Clone
2. `npm i`

The bug:
React autocompletion does not work when hoisting node modules.

To see it in action, head to `asd/src/App.tx` and try to autocomplete props inside of the Button component

The "asd" folder is a copy of https://github.com/mui-org/material-ui/tree/master/examples/create-react-app-with-typescript.
This happened to me in a real project where I use lerna with hoisting.
