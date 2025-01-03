# [Hugo](https://gohugo.io/) for [vedupraity.in](https://www.vedupraity.in)

### Directory Structure

```
.
├── archetypes
│   └── default.md
├── config
│   └── _default
│       └── hugo.yaml
├── content
│   ├── _index.html
│   └── tech
│       ├── _index.md
│       ├── gha
│       │   ├── _index.md
│       │   └── quickstart.html
│       └── hugo
│           ├── _index.md
│           └── quickstart.html
├── layouts
│   ├── _default
│   │   ├── baseof.html
│   │   ├── list.html
│   │   └── single.html
│   ├── index.html
│   └── partials
│       ├── breadcrumb.html
│       ├── footer.html
│       ├── header.html
│       ├── navbar.html
│       └── wip.html
```

### Build and Run for development

```
hugo server -D -w
```

### Build for production

```
hugo --minify
```
