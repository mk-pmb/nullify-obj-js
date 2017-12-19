
<!--#echo json="package.json" key="name" underline="=" -->
nullify-obj
===========
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Flat-copy an object&#39;s keys to a new one that has no prototype.
<!--/#echo -->


WYSIWYG:

<!--#include file="no.js" code="javascript" -->
<!--#verbatim lncnt="4" -->
```javascript
'use strict';
module.exports = function (o) { return Object.assign(Object.create(null), o); };
```
<!--/include-->



<!--#toc stop="scan" -->




&nbsp;


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
