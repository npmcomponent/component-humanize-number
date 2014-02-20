*This repository is a mirror of the [component](http://component.io) module [component/humanize-number](http://github.com/component/humanize-number). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-humanize-number`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# humanize-number

  Humanize a number `1000000.99` -> `1,000,000.99`

## Installation

    $ component install component/humanize-number

## Example

```js
var humanize = require('humanize-number');

humanize(1000);
// => '1,000'

humanize(1000.55, { delimiter: '.', separator: ',' });
// => '1.000,55'
```

## License

  MIT

