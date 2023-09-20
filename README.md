# vscode-snippets
A collection of snippets I use in my daily work

## Snippets

* [jest-react-starter](/jest-react-starter.json): A starter template for testing React components with Jest and RTL
  * Includes basic test case;
  * Includes automatic imports and name resolution based on the test file name (I assumes that the test file is named after the component, like `<ComponentName>.test.tsx`;
  * Includes automatic import of the component's type, assuming it's stored in a `types.ts` file at the root of the component folder;
  * Includes basic `renderComponent` function that accepts optional props you can pass to the component;
