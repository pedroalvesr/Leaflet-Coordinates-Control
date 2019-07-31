Leaflet Coordinates Control
===========================
Captures mouseclick and displays its coordinates with easy way to copy them.

Demo ([clik here](http://zimmicz.github.io/Leaflet-Coordinates-Control/))
----




## ![gyphy-mouse-coordinates-click-min](https://user-images.githubusercontent.com/22817118/62242745-3702ed00-b3b2-11e9-9220-7032e96b93ed.gif)

### Installation

#### Install via npm

```
npm i leaflet-coordinates-control
```
#### Include as ES6 Module

```js
import 'leaflet-coordinates-control';
import 'L.Control.Coordinates.css';
```

How to use
----------
	
	var c = L.control.coordinates().addTo(this.map);

        this.map.on('click', function (e) {
            c.setCoordinates(e);
        });
	
### Credit

This is my first leaflet plugin, this whole structure was based on the [zimmicz](https://github.com/zimmicz/Leaflet-Coordinates-Control) project. So don't be surprised to see somefamiliar code.
