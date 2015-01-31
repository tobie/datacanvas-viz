# datacanvas-viz

Quick d3.js-based visualization for the datacanvas project.

To view your sensor data: http://tobie.github.io/datacanvas-viz/?user=[YOUR-ID]&sensor=[airquality_raw|dust|humidity|light|sound|temperature|uv]

By default, samples one of 30 data points (once every 5 minutes) for the last week. This can be modifidied through the `sampling` and `since` query parameter, e.g.:

http://tobie.github.io/datacanvas-viz/?user=[YOUR-ID]&sensor=uv&sampling=1000&since=2015-01-30

More info on the datacanvas project here: http://datacanvas.org/sense-your-city/

![A humidity sensor somewhere in Bangalore](/screenshots/humidity.jpg)

![A light sensor somewhere in Shanghai](/screenshots/light.jpg)