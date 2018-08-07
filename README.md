# demo-spfx-webcomponents

Demo setup showing using web components in the SharePoint Framework

![Sample SharePoint Framework web part using a custom web component styled after the Office UI Fabric Button component](./assets/webpart.png)

## Minimal path to awesome

### Setup web components

```sh
cd ouif-components
npm i
npm run build
npm link
```

### Setup the SharePoint Framework project

```sh
cd spfx-151-webcomponents
npm i
npm link ouif-components
gulp serve
```