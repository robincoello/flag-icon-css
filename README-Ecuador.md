# flag-icon-css Version Ecuador

https://www.normalizacion.gob.ec/



```

<span class="flag-icon flag-icon-ec"></span>

```


Los códigos se basan en https://es.wikipedia.org/wiki/ISO_3166-2:EC

```

Código 	Nombre de las provincias
EC-A 	Provincia de Azuay
EC-B 	Provincia de Bolívar
EC-F 	Provincia de Cañar
EC-C 	Provincia de Carchi
EC-H 	Provincia de Chimborazo
EC-X 	Provincia de Cotopaxi
EC-O 	Provincia de El Oro
EC-E 	Provincia de Esmeraldas
EC-W 	Provincia de Galápagos
EC-G 	Provincia de Guayas
EC-I 	Provincia de Imbabura
EC-L 	Provincia de Loja
EC-R 	Provincia de Los Ríos
EC-M 	Provincia de Manabí
EC-S 	Provincia de Morona Santiago
EC-N 	Provincia de Napo
EC-D 	Provincia de Orellana
EC-Y 	Provincia de Pastaza
EC-P 	Provincia de Pichincha
EC-SE 	Provincia de Santa Elena
EC-SD 	Provincia de Santo Domingo de los Tsáchilas
EC-U 	Provincia de Sucumbíos
EC-T 	Provincia de Tungurahua
EC-Z 	Provincia de Zamora Chinchipe

```






> A collection of all country flags in SVG — plus the CSS for easier integration.
> See the [demo](https://flagicons.lipis.dev).

## Install

You can either [download](https://github.com/lipis/flag-icon-css/archive/master.zip)
the whole project as is or install it via Bower or NPM:

```bash
$ bower install flag-icon-css
$ npm install flag-icon-css
```

## Usage

For using the flags inline with text add the classes `.flag-icon` and
`.flag-icon-xx` (where `xx` is the
[ISO 3166-1-alpha-2 code](https://www.iso.org/obp/ui/#search/code/)
of a country) to an empty `<span>`. If you want to have a squared version flag
then add the class `flag-icon-squared` as well. Example:

```html
<span class="flag-icon flag-icon-gr"></span>
<span class="flag-icon flag-icon-gr flag-icon-squared"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`flag-icon-background` instead of `flag-icon` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 4 by 3 ratio or if it's squared
add also the `flag-icon-squared` class.

## Development

Run the `npm install` to install the dependencies after cloning the project and
you'll be able to:

To watch for changes and live reload if served

```bash
$ grunt
```

To build `*.less` files

```bash
$ grunt build
```

To serve it on `localhost:8000`

```bash
$ grunt connect
```

To have only specific countries in the css file, remove the ones that you don't
need from the
[`flag-icon-list.less`](https://github.com/lipis/flag-icon-css/blob/master/less/flag-icon-list.less)
file and build it again.

## Credits

This project wouldn't exist without the awesome and now deleted collection of
SVG flags by [koppi](https://github.com/koppi).

## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/lipis/flag-icon-css/graphs/contributors"><img src="https://opencollective.com/lipis/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/lipis/contribute)]

#### Individuals

<a href="https://opencollective.com/lipis"><img src="https://opencollective.com/lipis/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/lipis/contribute)]

<a href="https://opencollective.com/lipis/organization/0/website"><img src="https://opencollective.com/lipis/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/1/website"><img src="https://opencollective.com/lipis/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/2/website"><img src="https://opencollective.com/lipis/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/3/website"><img src="https://opencollective.com/lipis/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/4/website"><img src="https://opencollective.com/lipis/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/5/website"><img src="https://opencollective.com/lipis/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/6/website"><img src="https://opencollective.com/lipis/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/7/website"><img src="https://opencollective.com/lipis/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/8/website"><img src="https://opencollective.com/lipis/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/lipis/organization/9/website"><img src="https://opencollective.com/lipis/organization/9/avatar.svg"></a>
