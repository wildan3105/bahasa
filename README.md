# Example

```shell
$ npm install bahasa
```

```javascript
const {bahasaWords} = require('bahasa').default

// ES 2015
import {bahasaWords} = from 'bahasa'
const filtered = bahasaWords(
 'The new apple macbook will have touchbar',
 ['pro','touchbar']
)

console.log(filtered)
// The new apple macbook will have ***
```

