# d0

**d0** is a lightweight classless responsive pure CSS microframework.  

## Features

* Minimalist and lightweight (minified and gzipped CSS <3 KB)
* Styling is not based on classes, additional attributes and hacks
* Just tags and some cascading
* Uses native elements and behaviour when possible
* Valid CSS and HTML
* Pure CSS, no Javascript
* Basic elements typography
* Responsive wrapper, grid, nav, form, image
* Printable style
* Customizable with css variables
* Neutral defaults
* Does not use ``float``, ``!important``

## Components

* Typography
* Wrap (``max-width``)
* Grid
* Form (inline, stacked, aligned)
* Dropdown menu
* Popup
* Toggle element
* Modal dialog
* Gallery
* Tabs
* Table
* Alert
* Icon

## Getting Started

### Use from CDN

#### [jsDelivr](https://www.jsdelivr.com/package/npm/d0css)

```html
<link href="https://cdn.jsdelivr.net/npm/d0css@1/dist/d0.min.css" rel="stylesheet">
```

#### [GitCDN](https://gitcdn.link/)

```html
<link href="https://gitcdn.link/repo/vvvkor/d0/master/dist/d0.min.css" rel="stylesheet">
```

### Install with NPM

Install to your repository:
```
npm install d0css
```
Then use in your CSS file:
```css
@import "../node_modules/d0css/dist/d0.min.css";
```

### Install manually

Download minified [d0 files](https://github.com/vvvkor/d0/tree/master/dist).

```html
<link href="d0.min.css" rel="stylesheet">
```

## Customization

* ``--text`` - base text color; default: ``#222``
* ``--text-lite`` - lite text color; default: ``#999``
* ``--bg`` - base background color; default: ``#fff``
* ``--bg-pane`` - panel background color; default: ``rgba(0,0,0,.05)``
* ``--border`` - border style; default: ``thin solid rgba(0,0,0,.16)``
* ``--bg-hilite`` - highlighted element background; default: ``rgba(0,0,0,.05)``
* ``--text-hilite`` - highlighted element text color; default: ``inherit``
* ``--link`` - base link text color; default: ``#03b``
* ``--hover`` - hovered link text color; default: ``#003``
* ``--visited`` - visited link text color; default: ``#90c``
* ``--rad`` - border radius in ``em``s; default: ``.2``
* ``--gap`` - base gap for margins and paddings in ``em``s; default: ``1``
* ``--gap-rate`` - rate of vertical and horizontal gap; default: ``.5``
* ``--text-danger`` - danger text color; default: ``#c11``
* ``--bg-danger`` - danger alert background color; default: ``#f99``
* ``--bg-warning`` - warning alert background color; default: ``#fd6``
* ``--bg-success`` - success alert background color; default: ``#9da``
* ``--bg-info`` - info alert background color; default: ``#9ce``

## Browser Support

* IE 9 (menu: mobile style only; grid, form: desktop style only)
* IE 10+, Edge
* Latest Stable: Chrome, Firefox, Opera, Safari
* iOS 6-8
* Android 4.x

## Docs

[Docs and demo](https://vvvkor.github.io/d0/)

## License

[MIT](./LICENSE)
