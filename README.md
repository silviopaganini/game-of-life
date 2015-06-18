## Conway's Game of Life Browserify module 


### Install

```
$ npm install gof-array --save-dev

```


### Usage

```
var GoL = require('gof-array');
var world = new GoF(howManyBlocks, speed); // speed:int
world.restart()

function update()
{
	world.update();
	for (var i = 0; i < world.grid.length; i++) {
		var line = world.grid[i];
		
		for (var a = 0; a < line.length; a++) {
			// line[a] element true/false
		}
	}
	
	requestAnimationFrame(update);
}

```

[Live Demo](http://labs.fluuu.id/iso)
