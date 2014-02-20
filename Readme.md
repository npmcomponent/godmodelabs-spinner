*This repository is a mirror of the [component](http://component.io) module [godmodelabs/spinner](http://github.com/godmodelabs/spinner). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/godmodelabs-spinner`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Spinner

  Flexible spinner using canvas.

  ![js spinner component](http://i.imgur.com/Iyl0d.png)
  
  Check out the [demo](http://godmodelabs.github.com/spinner/)!

## Installation

```bash
$ component install godmodelabs/spinner
$ npm install spinner-component
```

## Example

```js
var Spinner = require('spinner');

var spinner = new Spinner;
document.body.appendChild(spinner.el);
```

## API
  
### Spinner#font(family)

  Change the font to `family`.

### Spinner#fontSize(n)

  Change the font size to `n`.

### Spinner#size(n)

  Change the indicator diameter to `n`, defaults to 50.

### Spinner#speed(n)

  Change the speed to `n` rpm, defaults to 60.

## License

  MIT
