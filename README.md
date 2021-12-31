# vercel-apollo-server-test

Just a test of Apollo Express Server deployment to Vercel

https://vercel-apollo-server-test.vercel.app/graphql

Send a POST request to query this endpoint:

curl --request POST \
  --header 'content-type: application/json' \
  --url 'https://vercel-apollo-server-test.vercel.app/graphql' \
  --data '{"query":"query { hello }"}'
{"data":{"hello":"world"}}
