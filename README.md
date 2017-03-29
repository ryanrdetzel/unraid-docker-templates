## Zoneminder (Official)
This uses an external mysql database so you'll have to use an existing mysql setup or spin up a docker.
Run this docker in attached mode to verify you can access the mysql server from within the docker.

```
docker run -i -it kylejohnson/zoneminder /bin/bash
mysql -h HOST_IP -uroot -p
```
You'll then need to change the host/name/user/pass in the zm.conf file that the docker uses. A basic zm.conf can be found in the stuff dir.
