# reproduction

Reproducing an error in signals

![Screenshot](image.png)

```
index.ts:778 Uncaught Error: Cycle detected
    at b.S (index.ts:778:3)
    at d2 (index.ts:49:36)
    at index.ts:172:2
    at index.ts:185:2
    at j (index.js:238:22)
    at D (render.js:42:2)
    at index.ts:27:11
b.S	@	index.ts:778
d2	@	index.ts:49
(anonymous)	@	index.ts:172
(anonymous)	@	index.ts:185
j	@	index.js:238
D	@	render.js:42
(anonymous)	@	index.ts:27
```
