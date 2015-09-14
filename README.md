# &lt;upper88-wordcloud&gt;

> Word Cloud custom element
>
> Work in progress, not really ready yet, but try it out and give your feedback!
>


## Demo

[Check it live!] not yet...

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install upper88-wordcloud --save
```

Or [download as ZIP](https://github.com/erikwett/upper88-wordcloud/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/upper88-wordcloud/upper88-wordcloud.html">
    ```

3. Start using it!

    ```html
    <upper88-wordcloud rows='[["Kenya", 7], ["Jamaica", 7], ["United States", 6], ["Great Britain", 4], ["Ethiopia", 3], ["Poland", 3], ["Canada", 2], ["Germany", 2], ["Russia", 2], ["Cuba", 2]]'></upper88-wordcloud>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
rows          | *Array*     | none         | An array of arrays. First value in each array is the text,second is the value
options       | *Object*    |              | Options. Current options are: maxFont (default 24), minFont (default 12)


## History

For detailed changelog, check [Releases](https://github.com/erikwett/upper88-wordcloud/releases). (Not much there yet...)

## Library used
[wordcloud2.js](https://github.com/timdream/wordcloud2.js) - word cloud library by [timdream](https://github.com/timdream).

## License

[MIT License](http://opensource.org/licenses/MIT) - so go ahead and use it!!


