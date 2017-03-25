# MKH Player - jQuery plugin for HTML 5 video and audio

## Usage

```javascript
$('audio').mkhPlayer(); // for audio file
$('video').mkhPlayer(); // for video file
```

## Demo

You can check the demo site [https://myokyawhtun.github.io/mkhplayer](https://myokyawhtun.github.io/mkhplayer).

### Sample

```html
<html>
	<head>
	...
	...
	<link rel="stylesheet" type="text/css" href="css/mkhplayer.default.css"/>
	...
	</head>
	<body>
	...
	...
		<audio id="music3" preload="metadata">
			<source src="media/interlude.mp3">
		</audio>

		<script type="text/javascript" src="https://code.jquery.com/jquery-1.7.1.min.js"></script>
		<script type="text/javascript" src="js/jquery.mkhplayer.js"></script>
		<script type="text/javascript">
			$(document).ready(function(){
				$('audio').mkhPlayer();
			});
		</script>
	</body>
</html>
```