*This repository is a mirror of the [component](http://component.io) module [stephenmathieson/rndid](http://github.com/stephenmathieson/rndid). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stephenmathieson-rndid`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# rndid

  generate a guaranteed unique id

## Installation

    $ component install stephenmathieson/rndid

## API

### rndid([prefix], [length])

  Return a guaranteed unique id of the provided `length`, optionally prefixed with `prefix`.

  If no length is provided, will use `rndid.defaultLength`.

### rndid.defaultLength

  Default length (7) of generated IDs.

## License

  MIT
