# jQuery Illuminate

This was a project that I built back in the day and thought I would put it up on GitHub ;) Learn how to use it below.

# How to use

1. Include all the necessary javascript files:

```
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js"></script>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.8.13/jquery-ui.min.js"></script>
<script type="text/javascript" src="jquery.illuminate.0.7.min.js"></script>
```

2. Create Your CSS/HTML object

```
<div id="button" style="background:#98cb00">Click Me</div>
```

3. Illuminate the CSS/HTML object

```
<script type="text/javascript">

    $(document).ready(function(){

        $('#button').illuminate();

    });

</script>
```

# Options
jQuery illuminate has several options which allow you to customize the illumination effect. The options are shown below:

```
{
    'intensity': 0.05,      //Intensity of the illumination 0.00% – 1.00%
    'color': '',                // illuminate color (default is background color)
    'blink': true,          //illumination will pulse/blink on and off
    'blinkSpeed': 600,      // # of millisectionds to pulse/blink on and off
    'outerGlow': true,      // true or false whether to add an outer glow effect
    'outerGlowSize': '30px',    // the size of the outerGlow illuminate
    'outerGlowColor': ''        // outer glow color (default is background color)
}
```

To add any or all of these options, the code would look as follows:

```
<script type="text/javascript">

$(document).ready(function(){

    $('#button').illuminate({

        'intensity': '0.3',

        'color': '#98cb00',

        'blink': 'true',

        'blinkSpeed': '1200',

        'outerGlow': 'true',

        'outerGlowSize': '30px',

        'outerGlowColor': '#98cb00'

    });

});

</script>
```
