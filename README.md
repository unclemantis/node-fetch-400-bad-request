# node-fetch-400-bad-request
fetch returns a 400 Bad Request upon POST to https://stacks-node-api.mainnet.stacks.co/v2/fees/transaction

### response result

```
Response {
  size: 0,
  timeout: 0,
  [Symbol(Body internals)]: {
    body: PassThrough {
      _readableState: [ReadableState],
      _events: [Object: null prototype],
      _eventsCount: 2,
      _maxListeners: undefined,
      _writableState: [WritableState],
      allowHalfOpen: true,
      [Symbol(kCapture)]: false,
      [Symbol(kCallback)]: null
    },
    disturbed: false,
    error: null
  },
  [Symbol(Response internals)]: {
    url: 'https://stacks-node-api.mainnet.stacks.co/v2/fees/transaction',
    status: 400,
    statusText: 'Bad Request',
    headers: Headers { [Symbol(map)]: [Object: null prototype] },
    counter: 0
  }
}
```
