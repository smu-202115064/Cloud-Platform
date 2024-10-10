## 실습 코드

```shell
docker build --tag pdocker .
docker images

docker tag pdocker:latest pdocker:v1.0.0
docker images
docker rmi pdocker:v1.0.0

docker run pdocker
docker run -p 5000:5000 pdocker
```
