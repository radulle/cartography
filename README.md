# Cartography

## [MOBAC (Mobile Atlas Creator)](https://mobac.sourceforge.io)

- Install app
- Install JRE/JDK if needed
- Copy `xml` files to `mapsources` to mobac
- Run `sh start.sh` on MacOS or `Mobile Atlas Creator.exe` on Win
- New Atlas (chose name)
- For use with OsmAnd it's best to pick `OsmAnd SQLite` format.
- Pick map source
- Pick zoom levels (take only what you need as it will impact file size)
- Select area you want to save (take only what you need as it will impact file size)
- Add selection/New (pick name)
- Create Atlas
- Repeat for each map source

### Google Satellite & Hubrid

No config required.

Optimal zoom levels from 12 to 16 (17 if area is not too large).

### Open Topo Map

No config required.

Optimal zoom levels from 11 to 15.

### Strava Heatmaps

No config required until zoom level 11.

For higher zoom levels authorization is required. Login to Strava and open [heatmaps](https://www.strava.com/heatmap) (having dedicated account might be a good idea). Substitute qiuery parameters X, Y and Z in auth XMLs for values in cookies which start with keyword CloudFront.

Optimal zoom levels from 11 to 15.

It's ok to skip errors since tiles are missing in areas where there are no activities recorded.

## [OsmAnd](https://osmand.net)

Available on mobile stores.

You will be prompted to download free routable offline vector OSM maps.

You will find folder where to copy downloaded maps in `OsmAnd / Settings / OsmAnd Settings / Data Storage Folder`.

Use downloaded maps as underlay (Satellite, Topo) or overlay (Strava heatmaps).

Tweak map views to your liking.
