# Muhammad Sayyedul Awwab

**Backend Software Engineer** · .NET Core · Dhaka, Bangladesh

I build backend systems: the APIs, the data models, and the business rules underneath them. I am working toward software architecture and technical leadership, designing systems that stay reliable and maintainable as they grow.

[![Website](https://img.shields.io/badge/Website-sayyedulawwab.com-1f2937)](https://sayyedulawwab.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayyedulawwab/) [![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@sayyedulawwab) [![Email](https://img.shields.io/badge/Email-sayyedulawwab%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:sayyedulawwab@gmail.com)

## What I work on

- **Now:** Senior Programmer at Epyllion Group, building an HRMS and enterprise business platform from the ground up in .NET Core with Clean Architecture, CQRS and DDD. I designed its approval engine (multi-step, parallel and dependency-based approvals), its role-based access control and hierarchy-based data permissions, and an Outbox-based notification system for email and in-app messages.
- **Before:** .NET Core microservices for a UK e-commerce platform of 30+ services at Echologyx, and legacy modernisation to .NET Core Web APIs plus payment flows at Bdjobs.

## Featured projects

- **[E-commerce Microservices](https://github.com/sayyedulawwab/EcommerceMicroservices)**: Catalog, Identity, Ordering, Cart and a simulated Payment service behind a YARP gateway. Placing an order runs as an event-driven flow over RabbitMQ and MassTransit, with a transactional outbox so events are not lost.
- **[Real-time Chat Service](https://github.com/sayyedulawwab/ChatService)**: one-to-one and group messaging over WebSockets with SignalR, using Clean Architecture and CQRS over SQL Server, MongoDB and Redis.

## Writing

I write about .NET Core, software architecture and databases at [sayyedulawwab.com/blog](https://sayyedulawwab.com/blog/) and on [Medium](https://medium.com/@sayyedulawwab).

## Toolbox

- **Backend & architecture:** C#, .NET Core, REST APIs, Clean Architecture, Vertical Slice Architecture, CQRS, DDD, Modular Monolith, xUnit
- **Data:** SQL Server, PostgreSQL, EF Core, Dapper, MongoDB, Redis
- **Distributed systems:** Microservices, RabbitMQ, MassTransit, NServiceBus, API gateways (YARP, Ocelot)
- **Delivery & observability:** Azure DevOps CI/CD, Docker, OpenTelemetry, Grafana, Prometheus, Loki, Tempo
