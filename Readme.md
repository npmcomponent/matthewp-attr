*This repository is a mirror of the [component](http://component.io) module [matthewp/attr](http://github.com/matthewp/attr). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/matthewp-attr`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# attr

  Cross-browser attribute manipulation.

## Installation

    $ component install matthewp/attr

## Examples

    attr(el).get('id'); // -> foo
	attr(el).set('id', 'foo'); // -> `attr(el)` to allow chaining

## API

### attr(el)

Returns a new instance of ``Attr``.

### Attr

An object for manipulation of attributes on an element.

#### Attr#get(name)

Gets the attribute ``name`` as a string.

#### Attr#set(name, val)

Sets the attribute ``name`` to ``val``.

#### Attr#has(name)

Returns true if the attribute ``name`` is set.

## License

  MIT
