# printLikePython

Do console.log() with just print()

## Installation

```js
npm i p13n
```

or

```js
npm i printLikePython
```

### How to Use

```js
const print = require("printLikePython");

print("Hello from printLikePython");
```

Below is the code in the printLikePython index.js file

```js
function print(val) {
  return console.log(val);
}

module.exports = print;
```
