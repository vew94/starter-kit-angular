# StarterKitAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.0.

# Setup

## Workspace

```
ng new starter-kit-angular --routing --style scss
```

## Install: Linter & Formatter

```
npm install --save-dev eslint prettier eslint-config-prettier
npm install --save-dev eslint-plugin-import
npm install --save-dev eslint-plugin-simple-import-sort
npm install --save-dev prettier-eslint
ng add @angular-eslint/schematics --skip-confirmation true
```

## Install: Utility

```
npm install --save-dev npm-run-all
npm install --save-dev @compodoc/compodoc
```

```
ng add @angular-jest/schematics
ng g @angular-jest/schematics:remove-karma starter-kit-angular
ng add @angular/material
```
