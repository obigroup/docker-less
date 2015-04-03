# Build:
```
docker build -t obigroup/less .
```

# Run:
```
docker run --rm -v `pwd`:/src -ti obigroup/less styles.less > styles.css
```
