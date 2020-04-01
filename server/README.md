# Denzel database

how to access the Express.js endpoints:

```sh
curl https://denzeldata.netlify.com/.netlify/functions/server/movies
curl https://denzeldata.netlify.com/.netlify/functions/server/movies/:id
curl https://denzeldata.netlify.com/.netlify/functions/server/movies/populate/:id
curl https://denzeldata.netlify.com/.netlify/functions/server/movies/search
curl --header "Content-Type: application/json" --request POST --data '{"json":"POST"}' https://denzeldata.netlify.com/.netlify/functions/server/movies/:id

```
