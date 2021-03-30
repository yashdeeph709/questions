Building robust,scalable and functional systems.

# Questions that I asked myself when I read about system design

1. Everything you need to know about http.
2. how ssl works.
3. how dns works and protocols 
4. sql vs nosql
5. query optimization in sql databases.
6. types and variety of databases and everything you need to know
7. What is load balancer? Types of load balancers, Cloud load balancers, in-premise load balancers and all you need to know about them.
8. What is database replication? and what are the types of it and how it works in various databases.
9. Preferred hardware for running database servers, web servers and load balancers,message queues 
10. replication methods like multi-masters and circular replication could help?
11. What are CDN? How they work? What options do we have? Can I have my own CDN?
12. What is cache? what are caching algorithms? How to build your own caches? How the caching works? What are the caching products are there in market for in-premise and cloud ? Caching strategies for data type,size and access patterns? And When can you use one? How to set cache expiry? 
13. Read this page Scaling Memcache at Facebook” published by Facebook [7].?
14. How to make an architecture fault tolerant and strategies to it.
15. Stateless web tier : where you store user session data in db so you can horizontally scale.
16. geoDNS its a DNS that can load balance across data centers for different geographically distributed location.
17. A previous study shows how Netflix implements asynchronous multi-data center replication
18. What are message queues? compare the options and how to use them and build architectures on top.
19. What are Database Sharding algorithams and approaches?
20. What is resharding when its required and what is celebrity problem?
21. https://github.com/donnemartin/system-design-primer best resource on system design?
22. What is rate limiting?
23. What is race conditions and synchronizations and locking mechanisms?
24. 


# Things to read
1. https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html
2. Bigtable paper by google
3. https://www.metabrew.com/article/anti-rdbms-a-list-of-distributed-key-value-stores
4. https://aws.amazon.com/simpledb/
5. https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/
6. http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html
7. https://nickcraver.com/blog/2013/11/22/what-it-takes-to-run-stack-overflow/
8. https://aws.amazon.com/cloudfront/dynamic-content/
9. https://github.com/donnemartin/system-design-primer
10. Reference materials
11. Rate-limiting strategies and techniques: https://cloud.google.com/solutions/rate-limitingstrategies-techniques
12. Twitter rate limits: https://developer.twitter.com/en/docs/basics/rate-limits
13. Google docs usage limits: https://developers.google.com/docs/api/limits
14. IBM microservices: https://www.ibm.com/cloud/learn/microservices
15. Throttle API requests for better throughput:
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-requestthrottling.html
16. Stripe rate limiters: https://stripe.com/blog/rate-limiters
17. Shopify REST Admin API rate limits: https://help.shopify.com/en/api/reference/restadmin-api-rate-limits
18. Better Rate Limiting With Redis Sorted Sets:
https://engineering.classdojo.com/blog/2015/02/06/rolling-rate-limiter/
19. System Design — Rate limiter and Data modelling:
https://medium.com/@saisandeepmopuri/system-design-rate-limiter-and-data-modelling9304b0d18250
20. How we built rate limiting capable of scaling to millions of domains:
https://blog.cloudflare.com/counting-things-a-lot-of-different-things/
21. Redis website: https://redis.io/
22. Lyft rate limiting: https://github.com/lyft/ratelimit
23. Scaling your API with rate limiters:
https://gist.github.com/ptarjan/e38f45f2dfe601419ca3af937fff574d#request-rate-limiter
24. What is edge computing: https://www.cloudflare.com/learning/serverless/glossary/whatis-edge-computing/
25. Rate Limit Requests with Iptables: https://blog.programster.org/rate-limit-requests-withiptables
26. Consistent Hashing: https://tom-e-white.com/2007/11/consistent-hashing.html
27. Dynamo: Amazon’s Highly Available Key-value Store: https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf
28. Cassandra - A Decentralized Structured Storage System: http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF
29. How Discord Scaled Elixir to 5,000,000 Concurrent Users: https://blog.discord.com/scaling-elixir-f9b8e1e7c29b
30. CS168: The Modern Algorithmic Toolbox Lecture #1: Introduction and Consistent Hashing: http://theory.stanford.edu/~tim/s16/l/l1.pdf
31. Maglev: A Fast and Reliable Software Network Load Balancer: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf