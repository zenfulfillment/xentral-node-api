# xentral node api

## Usage

```js
const xentral = require('xentral-node-api')({
  user: 'your-api-username',
  pass: 'your-api-password'
});

// Request orders
const res = await xentral.get('belege/auftraege');
```
