## Normalize

A very basic style reset included before all else. Included automatically.

```scss
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
}

body {
  font-size: 1em;
  line-height: 1.5789;
  margin: 0;
  padding: 0;
  perspective: 1500px;
  perspective-origin: 0% 50%;
  position: relative;
  text-rendering: optimizeLegibility;
}

h1,
h2,
h3,
h4,
h5,
p,
li {
  margin: 0;
  padding: 0;
}

* {
  box-sizing: border-box;
}

iframe[src^='//www.youtube.com'],
iframe[src^='//player.vimeo.com'] {
  width: 100%;
}
```