# MyPortfolio

## Portfolio with Angular
This portfolio is a responsive HTML CV website based on Bootstrap. 

<b>Technology:</b> Angular 11, BootStrap, HTML5, CSS3, TypeScripte, JQuery

<b>Web Site:</b> vinnamaral.github.io

## Libraries used
- AOS — Animate on scroll
- Typed.js — Animate typing text
- Fortawesome, Iconify design — Icons
- JQuery — Buttons events
- BootStrap4 — Set of CSS and JavaScript files that contain predefined rules.

## Angular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Deploy
 Open package.json and then, in script section add the following script.

"scripts": {
    // ...
    "deploy": "ng b --prod --base-href https://USERNAME.github.io/DEPOT_NAME/ && npx ngh --dir=dist/Project_Name"
},

And now, you can build and deploy to GitHub Pages with a single command: npm run deploy



