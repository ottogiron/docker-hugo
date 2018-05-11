# hugo

`hugo` is a container that convert markdown into html using [hugo static site generator](http://gohugo.io/).

## Usage

Look for available [tags](https://hub.docker.com/r/ottogiron/hugo/tags/)


```
# run the hugo container
docker run -e HUGO_BASE_URL=example.com -v /path/to/md:/src -v /path/to/html:/dest ottogiron/hugo
```



