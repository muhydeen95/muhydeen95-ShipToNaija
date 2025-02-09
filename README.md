# OnyxRevamped

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.11.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files. (N:B: If the compilation runs into "Javascript hemp out of memory, run `export NODE_OPTIONS=--max-old-space-size=4096`, as this was due to the size of country json file in the app).

## Project setup

Run `npm i` to install project dependencies. The node module will automatically be generated for the app.

## Folder Structure

The `src` folder house project with some module. The `appmodule` contains the project root, `@auth` for the authentication module, `@webapp` for the template layout (which comprises of all components for various pages), `@core` for the reusable modules(sahred, jsons, const etc.), `@directives` for the directive modules, `@partials` for all css variables and reusable styles (colour, button, typography etc.) and the `@store` for the notification store effect and future api purpose.


## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
