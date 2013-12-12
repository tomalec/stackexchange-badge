# &lt;se-badge&gt;

`<se-badge>` is a [Custom Element](https://github.com/polymer/CustomElements) with [StackExchange](http://api.stackexchange.com/) ([StackOverflow](http://stackoverflow.com/), [ServerFault](http://serverfault.com/), ...) user badge, that provides basic profile summary (gravatar, username, reputation, badge count).

> Maintained by [Tomek Wytrębowicz](https://github.com/tomalec).

## Demo

> [Check it live](http://tomalec.github.io/stackexchange-badge).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20131107/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="elements/se-badge.html">
	```

3. Start using it!

	```html
	<se-badge
		userId="868184" 
		site="stackoverflow"></se-badge>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`userId`   | *int*                     |                     | User id at given site.
`site`     | *string*  	   			   | `stackoverflow`     | Any [StackExchange](http://api.stackexchange.com/) site


## History

* v0.0.1 December 12, 2013
	* Initial commit

## License

[MIT License](http://opensource.org/licenses/MIT)