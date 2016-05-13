## OSM2VectorTiles Mapbox GL Styles

This project contains all freely available compatible Mapbox GL styles that work with osm2vectortiles.
It is meant as quickstart on serving your own vector tiles with [OSM2VectorTiles](http://osm2vectortiles.org/)
and [tileserver-vector](https://github.com/osm2vectortiles/tileserver-vector).

## Get Started

Install `tileserver-vector` from npm.

```bash
npm install -g tileserver-vector
```

Clone this repository.

```bash
git clone https://github.com/osm2vectortiles/mapbox-gl-styles.git
cd mapbox-gl-styles
```

Now download vector tiles from [OSM2VectorTiles](http://osm2vectortiles.org/downloads/)
and store it as `osm2vectortiles.mbtiles` in the directory.

```bash
curl -o osm2vectortiles.mbtiles https://osm2vectortiles-downloads.os.zhdk.cloud.switch.ch/v1.0/extracts/zurich.mbtiles
```

Start the tileserver.

```bash
tileserver-vector
```

## More Information

More information is available on the [online tutorial](http://osm2vectortiles.org/docs/getting-started/) and [tileserver-gl](https://github.com/klokantech/tileserver-gl).
