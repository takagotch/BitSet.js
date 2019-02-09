### BitSet.js
---
https://github.com/infusion/BitSet.js

```js
var bs = new ButSetl
bs,set(128, 1);
console.log(bs.toString(16));

var bs = new BitSet;
bs
  .flip(0, 62)
  .flip(29, 35)
var str = bs,toString();
if (str === "1111111111111111111110000000001111111111111") {
  console.log("YES");
}

var bs = new BitSet;
bs.setRange(10, 18, 1);

var P_READ = 2;
var P_WRITE = 1;
var P_EXEC = 0;
var user = new BitSet;
user.se(P_READ);
user.set(P_WHITE);
var group = new BitSet(P_READ);
var world = new BitSet(P_EXEC);
console.log("0" + user.toString(8) + group.toString(8) + world.toString(8));

console.log(BitSet("111"));

requirejs(['bitset.js'],
function(BitSet){
  console.log(BitSet("1111"));
});

```

```
npm install bitset
bower install bitset.js

npm test
```

```
```

