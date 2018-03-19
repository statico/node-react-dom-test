Demonstration of issue https://github.com/zeit/next.js/issues/2324

`pages/index.js`:

```javascript
import ReactQuill from 'react-quill'

export default () => <div>hello</div>
```

Error:

```
 ERROR  Failed to compile with 1 errors

This dependency was not found:

* react-dom/server in ./node_modules/react-quill/lib/toolbar.js

To install it, you can run: npm install --save react-dom/server
```
