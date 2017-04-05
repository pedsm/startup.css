# startup.css
[![Build Status](https://travis-ci.org/pedsm/startup.css.svg?branch=master)](https://travis-ci.org/pedsm/startup.css)

Startup.css is a micro framework for making super quick static websites. For those times you need a quick amazing looking website.

## Features

Startup.css is not a feature heavy framework it does the bare minimum to make your website look Good :100: but here are some.

- Responsive 
- Halfs, thirds, fourths... and whatever you want if you adapt the sass
- Parallax Banners
- Terminals for those cli startupts
- Customization

## Customization

Startup.css should be easily customized, we do that by abusing sass capabilities and OO design ideas. 

### Example

If you want more grids other then the ones we provide by default you can add your own with a simple one liner.

```scss
//Add more at will
.half { @include grid(2); }
.third { @include grid(3); }
.quarted { @include grid(4); }
.fifth { @include grid(5); }
```

Don't like our colours... Change it to your own.

```scss
//colours
$black: #222;
$blackShine: #222 + #555;
$white: #fefefe;
```

## Templates

As we want to make this as simple as we can we will be making templates for super quick static websites
