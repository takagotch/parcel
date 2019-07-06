### parcel
---
https://github.com/parcel-bundler/parcel

```sh
yarn global add parcel-bundler
npm install -g parcel-bundler

parcel index.html

yarn init -y
npm init -y
parcel watch index.html
parcel index.html about.html
parcel *.html
yarn add parcel-bundler --dev
npm install parcel-bundler --dev
npm install parcel-bundle --dev

yarn dev 
npm run dev
yarn build
npm run build
```

```js
exprt function render(){
}
import('./pages/about').then(function(page){
  page.render()
})
const page = await import('./pages/about')
page.render()

const pages = {
  about: import('./pages/about'),
  blog: import('./pages/blog')
}
async function renderPage(name){
  const page = await pages[name]
  return page.render()
}

import 'babel-polyfill'
import './app'

if(module.hot){
  module.hot.dispose(function(){
  })
  module.hot.accept(function(){
  })
}

import foo from "/assets/*.png";

module.exports = require('electron').ipcRenderer
import Apple from '/components/apple'
```

```
<html>
<body>
  <script src="./index.js"></script>
</body>
</html>
```

```
{
  "scripts": {
    "dev": "parcel <your entry file>",
    "build": "parcel build <your entry file>"
      }
}
```

```js
// packages/core/parcel-bundler/test/

```

