# await-sleep

Simple sleep with async/await

## Installation

```bash
npm install --save await-sleep
```

## Usage

```js
import * as sleep from 'await-sleep';

async function myAsyncFunction() {
  console.time('Sleeping');

  await sleep(1500);

  console.timeEnd('Sleeping'); // Sleeping: 1507.180ms
}

```
