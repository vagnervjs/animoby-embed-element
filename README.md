# &lt;animoby&gt;

Web Component wrapper for [AniMoby](https://www.animoby.com) player using Polymer.

> Maintained by [Vagner Santana](https://github.com/vagnervjs).

## Demo

> [Check it live](http://vagnervjs.github.io/animoby-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/animoby.html">
	```

3. Start using it!

	```html
	<animoby width="650" height="425" user="admin" proj="4e299d5c194f5f6652af4b0b96d34695" projid="1889"></animoby>```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`user`      | *string* | | **Required** user login
`proj`      | *string* 	| | **Required** project string id
`projid`   | *int* 	| | **Required** project id
`width`      | *int*                  | | iframe width
`height`      | *int*                  | | iframe height
`projtype`   | *default*, *slide*   | `default`| Type of AniMoby Project
`initialtime`      | *int* | `-1`               | 
`fullscreen`      | `true`, `false` | `false`               | 
`viewhint`       | `true`, `false` | `true`               | 
`minplayer`        | `true`, `false` | `false`               | 
`autoplay`          | `true`, `false` | `true`               | 
`frameborder`   | *int*                     | `0`               | iframe border


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 September 4, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)