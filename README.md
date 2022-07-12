# fridays-mock

Mockend for testing purpose

## Enpoints

### User

- https://mockend.com/vergissberlin/fridays-mock/user
- https://mockend.com/vergissberlin/fridays-mock/user/1

#### Example

```json
{
	"age": 77,
	"avatarUrl": "https://i.pravatar.cc/150?u=50446",
	"color": "#E76BE9",
	"email": "wohtcin@nlqxf.vc",
	"id": 1,
	"isPublic": true,
	"longDescription": "Nemo perspiciatis a reprehenderit illo dolor hic, fugiat quam consectetur ut. Fugit cum veniam, possimus delectus unde, laudantium consectetur a, reprehenderit a, consequatur aut reprehenderit.",
	"name": "nisi",
	"statusMessage": "watching Netflix"
}
```

### Posts

- https://mockend.com/vergissberlin/fridays-mock/post
- https://mockend.com/vergissberlin/fridays-mock/post/1

### Comments

- https://mockend.com/vergissberlin/fridays-mock/comment
- https://mockend.com/vergissberlin/fridays-mock/comments

## GraphQL

You can also use graphql to query the mockend:

```graphql
query {
  users {
    lastName,
    firstName
  }
}
```

[Here](https://mockend.com/vergissberlin/fridays-mock/graphql?query=query%20%7B%0A%20%20users%20%7B%0A%20%20%20%20lastName%2C%0A%20%20%20%20firstName%0A%20%20%7D%0A%7D) you can see it in action.

## Contribution

To add endpoints or make changes, follow the intructions https://docs.mockend.com/
