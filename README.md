# data-science-atelier

### Visit online:

- Production (main): https://roszcz.github.io

### Run locally

Tested with hugo `v0.68.3`

Build and serve with docker:
```sh
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.68.3 server
```

Build and serve with hugo:
```sh
hugo server --bind 0.0.0.0 --port 1234 -D
```
