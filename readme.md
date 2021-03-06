# Load YAML file

Read and parse a YAML file.

## Installation

```sh
npm install --save load-yaml-file
```

## Usage

```js
const loadYamlFile = require('load-yaml-file')

loadYamlFile('foo.yml').then(data => {
  console.log(data)
  //=> {foo: true}
})
```

## API

### loadYamlFile(filepath)

Returns a promise for the parsed YAML.

### loadYamlFile.sync(filepath)

Returns the parsed YAML.

## Related

- [load-json-file](https://github.com/sindresorhus/load-json-file) - Read and parse a JSON file
