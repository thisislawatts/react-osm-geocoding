# react-osm-geocoding

> Find address locations via OSM Nominatim

[![NPM](https://img.shields.io/npm/v/react-osm-geocoding.svg)](https://www.npmjs.com/package/react-osm-geocoding) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

![alt text](./images/search.png)
![alt text](./images/result.png)
## Install

```bash
npm install --save react-osm-geocoding
```

## Usage

```tsx
import React, { Component } from 'react'

import ReactOsmGeocoding from 'react-osm-geocoding'
import 'react-osm-geocoding/dist/index.css'

class Example extends Component {
  render() {
    return <ReactOsmGeocoding  callback={data => console.log(data)}/>
  }
}
```

## License

MIT © [SchemeSonic](https://github.com/SchemeSonic)
