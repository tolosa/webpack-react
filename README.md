# webpack-react learning

*Objective:* To manually set up and configure webpack from scratch for a React application, for learning purposes.

Run with `npm start`.

## Steps

1. Run `npm-init`.
2. Add webpack packages:

```
npm install --save-dev webpack webpack-dev-server
```

3. Add React packages:

```
npm install --save react react-dom
```

4. Add Babel packages:

```
npm install --save-dev @babel/core @babel/preset-env @babel/preset-react @babel/preset-stage-2 babel-loader
```

5. Add basic webpack configuration (on `webpack.config.js`).
6. Add `babel-loader` rule configuration to `webpack.config.js`.
7. Add basic babel configuration (on `.babelrc`).
