## next-docker
### init
```shell
docker-compose run --rm node sh

# in container
yarn install

exit
```

### Start dev container
http://localhost
```shell
docker-compose up next-dev -d
```

### Build
```shell
docker-compose run --rm node sh

# in container
yarn build
```

### Check build pages
http://localhost:8080
```shell
docker-compose up dev-static -d
```