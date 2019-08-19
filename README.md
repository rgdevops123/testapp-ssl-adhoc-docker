# testapp-ssl-adhoc-docker
Test Application to illustrate Python's Flask Adhoc SSL using Docker.

```
sudo docker build . -t rgdevops123/testapp-ssl-adhoc
sudo docker run -d --rm --name testapp-ssl-adhoc -p 5000:5000 rgdevops123/testapp-ssl-adhoc
```
