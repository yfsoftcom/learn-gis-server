# GeoServer

## Content List

- Summary
- Github
- Dockerfile
- Useage
- Issues
- TODOS

### Summary
[http://geoserver.org/](http://geoserver.org/)

### Github

[https://github.com/GeoNode/geoserver-docker](https://github.com/GeoNode/geoserver-docker)

### Useage

- install

  ```sh
  $ docker run --name "geoserver" --rm -d -p 9090:8080 neowaylabs/geoserver
  ```
  open [http://localhost:9090/geoserver](http://localhost:9090/geoserver)

  the default login info

  - User: `admin`
  - Pass: `geoserver`

- use in web