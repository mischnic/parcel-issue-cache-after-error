```
niklas@nmb:3653-resolver-jsx $ rm -rf .parcel-cache
niklas@nmb:3653-resolver-jsx $ parcel2 build index.html
🚨 Cannot find module './other' from '.../3653-resolver-jsx'
    at ResolverRunner.resolve (parcel/packages/core/core/src/ResolverRunner.js:64:15)
    at RequestGraph.resolvePath (parcel/packages/core/core/src/RequestGraph.js:402:24)
    at PromiseQueue._runFn (parcel/packages/core/utils/src/PromiseQueue.js:81:7)
    at PromiseQueue._next (parcel/packages/core/utils/src/PromiseQueue.js:69:5)
niklas@nmb:3653-resolver-jsx $ parcel2 build index.html
🚨 External modules are not supported when building for browser
    at Object.generateExternalImport (parcel/packages/shared/scope-hoisting/src/formats/global.js:32:9)
    at generateExternalImport (parcel/packages/shared/scope-hoisting/src/link.js:538:25)
```