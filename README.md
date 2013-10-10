# &lt;g-analytics&gt;

Web Component wrapper for Google Analytics using Polymer.

> Maintained by [Rob Dodson](https://github.com/robdodson).

## Demo

> [Check it live](http://robdodson.github.io/g-analytics).

## Usage

1. Import Web Components' polyfill:

  ```html
  <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130905/polymer.min.js"></script>
  ```

2. Import Custom Element:

  ```html
  <link rel="import" href="elements/g-analytics.html">
  ```

3. Start using it!

  ```html
  <g-analytics
    account="UA-XXXXXXXX-1"
    domain="foo.com">
  </g-analytics>
  ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 October 09, 2013
  * Initial commit

## License

[MIT License](http://opensource.org/licenses/MIT)