# eslint-plugin-sort-imports

ESLint rule to require sorting of import declarations. Does everything ESLint `sort-imports` does, but also allows ignoring member syntax order by defining additional value `'any'` for `memberSyntaxSortOrder` option.

## Install

`npm i @unemati/eslint-plugin-sort-imports -D`

## Usage

ESLint config:

```
plugins: ['@unemati/sort-imports'],
'@unemati/sort-imports/imports': ['error', {
    ignoreDeclarationSort: false,
    memberSyntaxSortOrder: 'any' // Ignore order of 'multiple', 'single' etc.
}],
```
