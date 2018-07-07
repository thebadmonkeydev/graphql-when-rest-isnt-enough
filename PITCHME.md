# GraphQL
### When REST isn't enough

---

## When REST isn't enough

  - Incomplete data sets
  - Multiple network requests for a full data context
  - Wasted bandwidth when the client needs a small data set

---

## Enter GraphQL
  - What it is
  - Where it came from
    - Rapid client development
    - API evolution

---

## GraphQL vs. REST
  - REST is:
    - Well known and intrinsic in Rails
    - Simpler with lower switching costs
    - Complex for production-scale applications
    - Ad-hoc and often internally motivated abstraction
  - GraphQL is:
    - Client-driven
    - Type system
      - Define-it-and-forget-it
      - Strongly typed
      - Clean layer of abstraction
    - Overly complex for small-scale deployments

---

## Should you adopt GraphQL?
  - They have more than one client application
  - A mobile client/focus on latency and bandwidth
  - Entrenched REST API with ballooning complexity
  - Decouple FE and BE development
  - Business perspective

---

## GraphQL the Ruby Way
  - The `graphql-ruby` gem
    - Existing implementation
    - New class-based implementation
  - Basic setup in a Rails app
  - Strategies for introducing GraphQL to existing REST APIs

---

## Conclusions and moving forward
  - Community
  - Adoption Strategies
    - Real world example from StackShare's feed
