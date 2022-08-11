# Simple JS projects to practice basic JS concepts

## Project list

- [GH-pages depoy](#gh-pages-depoy)

### Gh-pages depoy

Install [gh-pages](https://www.npmjs.com/package/gh-pages) packadge. <br>
`npm install gh-pages --save-dev` <br>
Update `package.json` file with new script

```
"scripts": {
  "deploy": "gh-pages -d ."
}
```

Where `.` is a root dir to publish. It can be replaced with `src`, `build` or `disc`.
