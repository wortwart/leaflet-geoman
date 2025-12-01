# Leaflet-Geoman

**Leaflet Plugin For Creating And Editing Geometry Layers**

Draw, Edit, Drag, Cut, Rotate, Split, Scale, Measure, Snap and Pin Layers

Supports Markers, CircleMarkers, Polylines, Polygons, Circles, Rectangles, ImageOverlays, LayerGroups, GeoJSON, MultiLineStrings and MultiPolygons

![Demo](https://assets.geoman.io/assets/draw-example.png)

## Changes from official version

This version is a fork of [Leaflet-Draw](https://github.com/Leaflet/Leaflet-draw) (version 2.18.3), with a few additions and fixes.

- Snapping.js: Fix issue with `_handleSnapLayerRemoval` error

## Documentation

Visit [geoman.io/docs](https://www.geoman.io/docs) to get started.

## Demo

Check out the full power of Leaflet-Geoman Pro on [geoman.io/demo](https://www.geoman.io/demo)

### Feature Requests

I'm adopting the Issue Management of lodash which means, feature requests get the "Feature Request" Label and then get closed.
You can upvote existing feature requests (or create new ones). Upvotes make me see how much a feature is requested and prioritize their implementation.
Please see the existing [Feature Requests here](https://github.com/geoman-io/leaflet-geoman/issues?q=is%3Aissue+is%3Aclosed+label%3A%22feature+request%22+sort%3Areactions-%2B1-desc) and upvote if you want them to be implemented.

### Developing

Clone the repository and then install all npm packages:

```
pnpm install
```

Compile and run `dev` watch version:

```
pnpm run start
```

Compile and run `build` version:

```
pnpm run prepare
```

Run cypress test:

```
pnpm run test
```

Open cypress window:

```
pnpm run cypress
```

Open eslint check:

```
pnpm run lint
```

Take a look into [CONTRIBUTING](./CONTRIBUTING.md)

### Credit

A big thanks goes to @Falke-Design, he invests a lot of time and takes good care of Leaflet-Geoman.

Thanks to @ryan-morris for the implementation of Typescript and support with Typescript questions.

As I never built a leaflet plugin before, I looked heavily into the code of leaflet.draw to find out how to do stuff. So don't be surprised to see some familiar code.

I also took a hard look at the great [L.GeometryUtil](https://github.com/makinacorpus/Leaflet.GeometryUtil) for some of my helper functions.

The Rotate Mode are only working because of the great calculation code of [L.Path.Transform](https://github.com/w8r/Leaflet.Path.Transform)
