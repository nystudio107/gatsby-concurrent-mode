# gatsby-concurrent-mode

## About `gatsby-concurrent-mode`

The `gatsby-concurrent-mode` plugin enables [Concurrent Mode](https://reactjs.org/docs/concurrent-mode-intro.html) in in React for Gatsby projects

This is based on [Wei's](https://twitter.com/wgao19) blog [Play with React Concurrent Mode with Your Gatsby Site](https://aworkinprogress.dev/play-concurrent-mode-with-your-gatsby-site/) with code from [Fredrik Höglund](https://twitter.com/EphemeralCircle)

## Installing `gatsby-concurrent-mode`

```bash
yarn add gatsby-concurrent-mode
```

or

```bash
npm install --save gatsby-concurrent-mode
```

## Using `gatsby-concurrent-mode`

In your `gatsby-config.js` file add this to your `plugins:`:

```js
module.exports = {
  plugins: ['gatsby-concurrent-mode']
};
```
