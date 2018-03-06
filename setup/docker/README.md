```bash
mkdir /tmp/mongo
sudo docker run -d -p 27017:27017 -v /tmp/mongo:/data/db mongo
```

# Resources
- https://store.docker.com/images/mongo
- https://www.thachmai.info/2015/04/30/running-mongodb-container/