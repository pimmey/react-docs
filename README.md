# React documentation
## Introduction
Welcome! First of all, thank you for purchasing this theme. We prepared a throughout documentation to make your experience as pleasant as possible. We tried to cover every aspect of this theme, however, if you still have any questions or need clarification, feel free to email us via [user's page contact form](http://themeforest.net/user/pimmey#contact?rel=pimmey).

This theme is built using [Materialize](http://materializecss.com/), a modern responsive front-end framework based on Material Design. Make sure you visit their web-site to learn more about it. Feel free to use all of the elements that framework provides.

## Requirements
This theme requires a pretty basic setup. In fact, the only thing your server needs is PHP installed, which is usually 99.9% of the cases. If you happend to be that 0.1%, please contact your hosting administrator and let him know you need PHP installed on your server. PHP is needed for the Contact form to function, but if you don't need that, any kind of hosting will do the trick.

Wata works great in all of the modern browsers, as well as mobile browsers. It supports Internet Explorer 10+, except for some advanced features, but we've written fallbacks for that.

## Installation
Installing our theme is extremely simple — just upload all the files to your server. In fact, you can test your theme locally as well, except for the contact form functionality, which requires a server side language.

## File structure
```
├── assets/
│   ├── config/
│   ├── css/
│   ├── font/
│   ├── images/
│   ├── js/
├── build/
├── libs/
├── mailer/
│   ├── templates/
│   src/
│   ├── jade/
│   ├── sass/
```

## Development process
The theme was programmed using two wonderful technologies - [Sass](http://sass-lang.com/) for the styles and [Jade](http://jade-lang.com/) to generate HTML files.

### Sass
> Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.

Writing styles with Sass is a pure pleasure. We've structured React's components to make them easily accessible and editable. The main file is `react.scss`, which contains `@import`s from all of the components, like common styles, buttons, modals, etc.

#### Colors
The color variables are defined in `_constant-colors.scss` file. The reason for its name is that we also include skin file with colors, which are not constant per page. We've also included `_materialize-color.scss` to access the `color('name', 'shade')` function, which is provided by Materialize's source and allows you to easily use the (Material design palette)[materializecss.com/color.html#palette].

#### Media query ranges
You can define your own media query ranges for small, middle and large displays. The variables are defined in `_media-query-ranges.scss`.

#### 
