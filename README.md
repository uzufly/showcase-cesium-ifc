# EPFL/CNPA · UE BIM · Cesium/IFC Showcase

[![Netlify Status](https://api.netlify.com/api/v1/badges/12a9eb3e-507d-47e9-b2e6-02fe9fcd5430/deploy-status)](https://app.netlify.com/sites/showcase-cesium-ifc/deploys) [![Build and deploy to Pages](https://github.com/uzufly/showcase-cesium-ifc/actions/workflows/pages.yml/badge.svg)](https://github.com/uzufly/showcase-cesium-ifc/actions/workflows/pages.yml)

Showcases the import of a BIM IFC model onto a Cesium 3D photorealistic environment — the neighborhood of the [‹Caserne des Vernets›](https://goo.gl/maps/85u1oCvbX7NPKHAz8) construction site, in Praille-Acacias-Vernets / Geneva.

<img src="src/assets/img/screencopy.png" height="450" alt="‹Cesium/IFC Showcase› webapp · screencopy">

## Credits

A partnership research project of [EPFL/ENAC-CNAC](https://www.epfl.ch/labs/cnpa/fr/) and [Uzufly](https://uzufly.com/), Lausanne / Switzerland.

Uzufly flew its drone over the area in 02.2023 and assembled the pictures in a [3D Tileset](https://cesium.com/why-cesium/3d-tiles/).

Built with [IFC.js](https://github.com/IFCjs), [Lit.dev](https://lit.dev/) and the [Cesium.js](https://cesium.com/platform/cesiumjs/) 3D geospatial visualization platform.

## Setup

```shell
npm install
```

## Dev

To start a development server, watching, building and hot-reloading continuously:

```shell
npm start
```

To build and bundle the sources (output in `dist/` subfolder):

```shell
npm run build
```

## License

Copyright 2023 Uzufly SÀRL  
Licensed under the [Apache License, Version 2.0](LICENSE).