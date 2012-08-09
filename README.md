#jquery-collapsibleFieldset

##Overview
A jQuery plugin for collapsible fieldsets. When the legend of the
fieldset is clicked, the fieldset is collapsed or expanded.

---

##Usage

````html
<fieldset id="myfieldset">
    <legend>My Fieldset</legend>
...
</fieldset>
````

````javascript
$('#myfieldset').collapsible();
````

##Styling

The following span is appended to the fieldset's legend to allow for "graphic" indicators:
````html
<span class="collapsible-indicator"></span>
````

The CSS class `collapsed` is applied to the fieldset element when it is collapsed.

##Options

###collapse
Callback function invoked after fieldset is collapsed.

###expand
Callback function invoked after fieldset is expanded.

##Copyright and License
Copyright (c) 2012 Rex McConnell.

The jQuery Collapsible Fieldset plugin is licensed under the [MIT license](http://rexmac.github.com/license/mit.txt).
