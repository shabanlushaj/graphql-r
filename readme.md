# GRAPHQL SERVER WITH APOLLO

## Scripts  

Install dependencies :

`npm i`

To start the express server :

`npm run start`

Build for production :  

`npm run build`

&nbsp;

## Using GraphQL schema with Playground

Follow link :

<http://localhost:9000/api>

Query listings:

```query{
  listings{
    id
    title
    price
  }
}
```

Mutation:

```mutation{
  deleteListing(id: "001"){
    id 
    title
  }
}
```
