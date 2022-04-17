# Common Functions

Some common functions. 

## Doc

### isObject

```ts
isObject(object: any): boolean
```

Determines if `object` is an object. 

### clone

```ts
clone(object: any, target?: (array, object), onconflict?: (string|function)): any
```

Deep clones an `object` into `target` if `target` exists. The cloned object will be returned.

The `conflict` function will be used along with `key` , `target` and `object` , whenever the cloning `key` already exists in `target` . The default of `conflict` function is a string `'overwrite'` , with which the value in `target` will be overwritten.

### createElement

```ts
createElement(tag: string, attributes?: object, parent?: Element): Element
```

Creates an element by `tag` , setups its `attributes` if there's any, and appends it to the `parent` element if provided.

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright © ROC 110 (2021), veringsek