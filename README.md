# rn-fetch

clone of whatwg-fetch with minimal changes:
- support `res.arrayBuffer()`
- export as a module

## Usage

```js
import rnfetch from 'rn-fetch'

rnfetch(url) // use like you would fetch
  .then(res => res.arrayBuffer())
  .then(doAmazingArrayBufferStuff)
```
