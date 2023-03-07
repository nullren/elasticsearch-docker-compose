# elasticsearch-docker-compose

Built from https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html

Copy the `.env-example` file to `.env` and modify accordingly. Then just start the cluster by bringing docker up, eg `docker compose up`.

Once up, navigate to http://localhost:5601/.

You can query elasticsearch directly with curl.

```
curl --insecure \
  --user elastic:$ELASTIC_PASSWORD \
  https://localhost:9200
```
