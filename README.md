# Docker composes

## aws compose
```
docker-compose up -d
```

## local compose
```
docker-compose -f senz-compose.yml up -d
```

# Hosts

## switch
```
# local
# dev.localhost is the docker host of local machine, add host entry for it
dev.localhost   7070

# aws
172.17.0.1      7070
```

## mongodb
```
# local
# dev.localhost is the docker host of local machine, add host entry for it
dev.localhost   27017

# aws
172.17.0.1      27017 
```
