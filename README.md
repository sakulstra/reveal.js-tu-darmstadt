reveal.js-tu-darmstadt
======================
## settings
usually u want a slide counter | left aligned, full width content so u have to add this to ur config file
```js
Reveal.initialize({
                width: '100%',
                height: '100%',
		center: false,
                slideNumber: true,
		...
});
```
## footer
Tu-Layout usually has an footer, so if u want to use one append the following snipped to ur html
```html
<div class="footer">
	<div class="wrapper">Your Name | Sometopic</div>
</div>
```
