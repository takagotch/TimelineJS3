### timelinejs3
---
https://github.com/NUKnightLab/TimelineJS3

```html
<link title="timeline-styles" rel="stylesheet" href="https://cdn.knightlab.com/libs/timeline3/latest/css/timeline.csss">
<script src="https://cdn.knightlab.com/libs/timeline3/latest/js/timeline.js"></script>
<div id='timeline-embed' style="width: 100%; height: 600px"></dov>
<script type="text/javascript">
  timeline = new TL.Timeline('timeline-embed', 'https://docs.google.com/spreadsheets/d/xxxxxxxxxxxxxxx/pubhtml');
</script>

<script type="text/javascript">
  var timeline_json = make_the_json();
  window.timeline = new TL.Timeline('timeline-embed', timeline_json);
</script>

<script type="text/javascript">
  var additionalOptions = {
    start-at_end: true,
    default_bg_color: {r:0, g:0, b:0},
    timenav_height: 250
  }
  timeline = new TL.Timeline('timeline-embed',
    'https://docs.google.com/spreadsheets/d/xxxxxxxxxxxx/pubhtml',
    additionalOptions);
</script>

<link title="timeline-styles" rel="stylesheet"
  href="https://cdn.knightlab.com/libs/timeline3/latest/css/timeline.css">
<link title="timeline-styles" rel="stylesheet"
  href="https://cdn.knightlab.com/libs/timeline3/latest/css/fonts/font.abril-droidsans.css">
```

```js
var options = {
  hash_bookmark: false,
  initialz_zoom: 5
}
var timeline = new TL.Timeline('timeline-embed',
  'https://docs.google.com/spreadsheets/d/xxxxxxxxxxxxx/pubtml');
```

