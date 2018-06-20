# squarespace node api

## Usage

```js
const squarespace = require('squarespace-node-api')({
  apiKey: 'your-squarespace-api-key'
});

squarespace.get('orders')
  .then((res) => console.log(res.Data));
```
