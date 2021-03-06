# \<letterscroll-element\>

A simple scroller with letters on the side.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="my-element.html">
    <link rel="import" href="../other-element/other-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<letterscroll-element>
	<div slot="child" value="A">A</div>
  
    <div slot="child" value="Ab">Ab</div>
  
    <div slot="child" value="B">B</div>
  
    <div slot="child" value="Bb">Bb</div>
  
    <div slot="child" value="C">C</div>
  
    <div slot="child" value="Cb">Cb</div>
  
    <div slot="child" value="D">D</div>
  
    <div slot="child" value="Db">Db</div>
  
    <div slot="child" value="E">E</div>
</letterscroll-element>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
