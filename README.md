# python-graph-sql
### Structures
```
.
├── data.py                         # will contain the logic of the @rateLimit directive
├── directives
│   ├── auth.py                         # will contain the logic of the @auth directive
│   ├── __init__.py
│   └── rate_limiting.py                # will contain the logic of the @rateLimit directive
├── app.py                          # entrypoint of our application. In charge of the initialization of the tartiflette-aiohttp server
├── __init__.py
├── __main__.py
├── mutation_resolvers.py           # will contain the Mutation resolvers
├── query_resolvers.py              # will contain the Query resolvers
├── README.md
├── sdl                             # directory which will contain our SDL (Schema Definition Language) files
│   ├── Mutation.graphql                # schema with our Mutation type
│   ├── Query.graphql                   # schema with our Query type
│   └── Subscription.graphql            # schema with our Subscription type
├── subscription_resolvers.py       # will contain the Subscription resolvers
├── tree.txt
```

### Prerequisites
- python 3.x
- beatutiful girl
- handsome boy

### Run code
`> python -m python-graph-sql `