# \<calendar-component\>

Web component for displaying items in calendar view

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

## Demo
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="calendar-component.html">
    	<script>
	    	document.addEventListener('WebComponentsReady', function() {
	    		var calendar = document.querySelector('calendar-component');
      		calendar.addEventListener('event-clicked', function(e) {
    				alert('Event clicked : ['+e.detail.subject+']');
    			});
		})
	  </script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<calendar-component active-date="2018-08-01" items='[{"date":"2018-08-08T20:00","subject":"Meeting", "theme" : "primary"}, {"date":"2018-08-14T12:30","subject":"Dentist Appointment", "theme" : "contrast primary"}, {"date":"2018-08-24T19:30","subject":"Dinner with Friends", "theme" : "success primary"}]'></calendar-component>
```
