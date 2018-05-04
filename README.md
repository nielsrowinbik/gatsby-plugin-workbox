# gatsby-plugin-workbox

Adds drop-in support for making a Gatsby site work offline and more resistant to
bad network connections. It generates a service worker using [Workbox](https://developers.google.com/web/tools/workbox/) for the site and loads the
service worker into the client.

If you're using this plugin with `gatsby-plugin-manifest` (recommended) this
plugin should be listed _after_ that plugin so the manifest file can be included
in the service worker.

## Install

`npm install --save gatsby-plugin-workbox`

## How to use

```javascript
// In your gatsby-config.js
plugins: [`gatsby-plugin-workbox`];
```
