# SVENJSX loader for Webpack

Add the loader to your Webpack config, like so:

```
module: {
  rules: [
       {test: /\.jsx$/, enforce: "pre", loaders: ['svenjsx-loader']}
  ]
}
```
This will convert the JSX syntax before any other processing is done.
