# Valkey Hackathon — Projects & Challenges

📅 June 20–21, 2026 | 📍 Amazon HYD13, Hyderabad | 🏁 Grace period until July 5

---

## About

[Valkey](https://valkey.io) is an open source (BSD) high-performance key/value datastore that supports a variety of workloads such as caching, message queues, and can act as a primary database. The project is backed by the Linux Foundation, ensuring it will remain open source forever.

Teams of **2 to 4** participants will choose one of the proposed projects below — or propose their own novel use case — and build a complete, end-to-end open source contribution submitted as a GitHub pull request. See the [README](./README.md) for full hackathon dynamics, timeline, and prizes.

---

## Challenge Tracks

Participants can choose between two challenge tracks:

### 🔌 Track A — Framework/Library/Project Integration

Integrate Valkey as a first-party backend into an existing open source framework, library, or platform. The goal is to submit a PR to the upstream project.

### 🚀 Track B — Build an Application

Build a complete application powered by Valkey that demonstrates its capabilities. The goal is to create a new open source project or contribute to an existing Valkey demo/tool.

---

## Track A — Integration Projects

| \# | Type | Track | Language | Project | Description |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1 | Integration | Web Framework | Java | [Spring.IO](https://github.com/spring-projects/spring-framework) | A first‑party Valkey integration in the Spring Framework delivers native support via Spring Data. It ensures API consistency, shared testing, and unified documentation using the same CI pipelines and security patches as other modules. |
| 2 | Integration | Web Framework | PHP | [Symfony](https://github.com/symfony/symfony) | Symfony is a PHP framework for web and console applications and a set of reusable PHP components. Add native Valkey support for caching, sessions, and lock components. |
| 3 | Integration | Messaging / Queue Library | Python | [Celery](https://github.com/celery/celery) | Integrating Valkey natively into Celery as a broker or result backend. A first-party driver simplifies configuration, ensures optimized serialization, and reduces external dependency risks. |
| 4 | Integration | CMS Framework | PHP | [WordPress](https://github.com/WordPress/wordpress-develop) | Add a first‑party Valkey integration to WordPress for native, high‑performance caching for object storage, session data, and transients using [GLIDE for PHP](https://github.com/valkey-io/valkey-glide-php). |
| 5 | Integration | Messaging / Queue Library | JavaScript | [BullMQ](https://github.com/taskforcesh/bullmq) | A first‑party Valkey integration for BullMQ gives the queue library native, battle‑tested support. Because BullMQ already relies on Redis commands, switching to Valkey requires no code changes — a first‑party driver ensures API consistency and CI testing. |
| 6 | Integration | Web Framework | Python | [Flask](https://github.com/pallets/flask) | Flask is a lightweight WSGI web application framework. Add native Valkey support for caching, rate limiting, and session management. |
| 7 | Integration | Session Library | Python | [Flask-Session](http://github.com/pallets-eco/flask-session/) | Add Valkey as a native session backend in Flask-Session making migrations from Redis trivial since Valkey is a drop-in replacement for Redis 7.2. |
| 8 | Integration | Web Framework | Python | [FastAPI](https://github.com/fastapi/fastapi) | FastAPI framework, high performance, easy to learn, fast to code. Add native Valkey support for caching, session management, and rate limiting. |
| 9 | Integration | Web Framework | Python | [Starlette](https://github.com/encode/starlette) | Starlette is a lightweight ASGI framework/toolkit ideal for building async web services. Currently supports Redis through starlette-sessions — add first-party Valkey support. |
| 10 | Integration | Web Framework | PHP | [Laravel](https://github.com/laravel/laravel) | Laravel currently has support for Redis. Add first-party integration of Valkey using [GLIDE for PHP](https://github.com/valkey-io/valkey-glide-php). |
| 11 | Integration | Web Framework | PHP | [CodeIgniter4](https://github.com/codeigniter4/CodeIgniter4) | CodeIgniter is a powerful PHP framework with a small footprint. Currently supports Redis for caching — add first-party Valkey support. |
| 12 | Integration | Web Framework | Ruby | [Ruby on Rails](https://github.com/rails/rails) | Rails currently uses Redis for Action Cable, caching, and Active Job. Add native Valkey support using [GLIDE](https://github.com/valkey-io/valkey-glide/) for enhanced cluster support and multiplexing. |
| 13 | Integration | Messaging / Queue Library | Ruby | [Sidekiq](https://github.com/sidekiq/sidekiq) | Simple, efficient background processing for Ruby. Currently supports Redis — add first-party Valkey support using [GLIDE](https://github.com/valkey-io/valkey-glide/) client for multiplexing, global SCAN, MGET, MSET and Cluster support. |
| 14 | Integration | Proxy | Go | [Envoy Proxy](https://github.com/envoyproxy/envoy) | Envoy is a CNCF Graduated project. Cloud-native high-performance edge/middle/service proxy. Currently supports [Redis protocol](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/other_protocols/redis). Add Valkey as a first-party integration using GLIDE for Go. |
| 15 | Integration | JS Runtime | JavaScript | [Bun](https://github.com/oven-sh/bun) | Bun is an incredibly fast JavaScript runtime, bundler, test runner, and package manager. Add support for Valkey besides already existing [Redis](https://bun.com/docs/runtime/redis) using [GLIDE](https://github.com/valkey-io/valkey-glide/). |
| 16 | Integration | AI/ML LLM Engine | Python | [vLLM](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs. Add Valkey as a distributed KV cache and request deduplication layer. |
| 17 | Integration | AI/ML Platform | Python | [LangChain](https://github.com/langchain-ai/langchain) | LangChain currently supports [Redis](https://github.com/langchain-ai/langchain-redis). Add support for [Valkey Vector Similarity Search](https://github.com/valkey-io/valkey-search) for higher throughput, lower latency, and continuous OSS support. |
| 18 | Integration | AI/ML Agentic | Python | [CrewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating autonomous AI agents. Add Valkey as a memory/cache backend for agent state, conversation history, and shared context. |
| 19 | Integration | AI/ML Agentic | Python | [LlamaIndex](https://github.com/run-llama/llama_index) | The leading framework for building LLM-powered agents over your data. Add native Valkey support for vector store, chat memory, and document store backends. |
| 20 | Integration | AI/ML Agentic | Python | [Agno](https://github.com/agno-agi/agno) | Agno is a framework for building AI agents. Currently supports Redis for session storage. Add first-party Valkey support using [GLIDE](https://github.com/valkey-io/valkey-glide/) for agent storage, team state, and workflow persistence. |
| 21 | Integration | AI/ML Gateway | Python | [LiteLLM](https://github.com/BerriAI/litellm) | LiteLLM is a unified API gateway for 100+ LLM providers. Currently uses Redis for caching, rate limiting, and semantic cache. Add native Valkey support for improved performance and open source alignment. |
| 22 | Integration | AI/ML Framework | Python | [Feast](https://github.com/feast-dev/feast) | Feast (Feature Store) for machine learning. Currently supports [Redis](https://docs.feast.dev/reference/online-stores/redis) — add Valkey as an Online Datastore. |
| 23 | Integration | AI/ML Framework | Python | [Ray](https://github.com/ray-project/ray) | Ray is an AI compute engine for distributed runtime and AI libraries. Add Valkey as a state store and object store backend. |
| 24 | Integration | AI/ML RAG Engine | Python | [RAGFlow](https://github.com/infiniflow/ragflow) | RAGFlow is a leading open-source RAG engine. Add Valkey as a cache and vector search backend for improved retrieval performance. |
| 25 | Integration | AI/ML Deep Research | Python | [DeerFlow](https://github.com/bytedance/deer-flow) | DeerFlow is a community-driven Deep Research framework. Add Valkey for caching web search results and intermediate research state. |
| 26 | Integration | Ops / Workflow | Python | [Apache Airflow](https://github.com/apache/airflow) | A platform to programmatically author, schedule, and monitor workflows. Currently supports [Redis](https://airflow.apache.org/docs/apache-airflow-providers-redis/stable/index.html) — add native Valkey provider. |
| 27 | Integration | Websockets | JavaScript | [Socket.IO](https://github.com/socketio/socket.io/) | Bidirectional and low-latency communication for every platform. Currently supports [Redis adapter](https://socket.io/docs/v4/redis-adapter/) — add native Valkey adapter. |
| 28 | Integration | Messaging / Queue Platform | Java | [Apache Kafka](https://github.com/apache/kafka) | Valkey Kafka Connector — Add Valkey as a sink connector for real-time cache updates from Kafka event streams. |
| 29 | Integration | Distributed SQL | Java | [Trino](https://github.com/trinodb/trino) | Trino, the distributed SQL query engine for big data. Currently has a [Redis connector](https://trino.io/docs/current/connector/redis.html) — add native Valkey connector. |
| 30 | Integration | e-Commerce | PHP | [OpenCart](https://github.com/opencart/opencart) | An open source PHP-based online e-commerce solution. Add Valkey for caching and session management. |
| 31 | Integration | e-Commerce | PHP | [PrestaShop](https://github.com/PrestaShop/PrestaShop) | The universal open-source software platform to build your e-commerce solution. Add Valkey for caching and session management. |
| 32 | Integration | e-Commerce | PHP | [Magento 2](https://github.com/magento/magento2) | Magento Open Source delivers basic eCommerce capabilities. Add native Valkey cache backend support. |
| 33 | Integration | PaaS Platform | JavaScript | [Coolify](https://github.com/coollabsio/coolify) | Self-hostable PaaS alternative to Vercel/Heroku. Currently supports [Redis](https://coolify.io/docs/databases/redis) and Dragonfly — add native Valkey support. |
| 34 | Integration | Workflow Automation | JavaScript | [n8n](https://github.com/n8n-io/n8n) | n8n is a workflow automation platform. Currently uses Redis for queue mode, caching, and AI agent memory. Add native Valkey support for all Redis-dependent components. |
| 35 | Integration | Serverless Framework | JavaScript | [Serverless Framework](https://github.com/serverless/serverless) | Build applications on AWS Lambda and other FaaS platforms. Add Valkey as a supported cache/state store component for serverless architectures. |
| 36 | Integration | IaC Platform | Go | [SST](https://github.com/anomalyco/sst) | SST is an infrastructure-as-code framework. Currently has a Redis component backed by ElastiCache — add native Valkey component support. |
| 37 | Integration | Security / IdP | Python | [Authentik](https://github.com/goauthentik/authentik) | Open-source Identity Provider for modern SSO. Previously [removed Redis](https://goauthentik.io/blog/2025-11-13-we-removed-redis/) — integrate Valkey as a proper OSS-aligned caching layer. |
| 38 | Integration | CDC | Java | [Debezium](https://github.com/debezium/debezium) | Debezium is a distributed platform for change data capture. Add Valkey as a sink for transparent caching based on Write Ahead Log events. |
| 39 | Integration | Streaming | Rust | [Apache DataFusion](https://github.com/apache/datafusion) | DataFusion is an extensible query engine. Add Valkey as a cache layer for query results and intermediate computation state. |
| 40 | Integration | Big Data | Scala/Java | [Apache Spark](https://github.com/apache/spark) | Spark is a unified analytics engine. Add Valkey as a shuffle store and RDD caching backend for improved performance. |
| 41 | Integration | Streaming | Go/C++ | [Redpanda](https://github.com/redpanda-data/redpanda) | Redpanda is a Kafka-compatible streaming data platform. Add Valkey integration for consumer group state and caching. |
| 42 | Integration | Database Adapter | Python | [ExtendDB](https://github.com/ExtendDB/extenddb) | ExtendDB is a DynamoDB-compatible adapter with pluggable storage backends. Add Valkey as a storage backend for ultra-fast key-value operations using the DynamoDB API. |
| 43 | Integration | IaC / Provisioning | Go | [OpenTofu](https://opentofu.org/) / [Terraform](https://github.com/hashicorp/terraform) | Add a Valkey provider for OpenTofu/Terraform to manage Valkey clusters, configurations, and ACLs as infrastructure-as-code. |
| 44 | Integration | API / Query Language | JavaScript | [GraphQL](https://graphql.org/) | Build a Valkey-backed GraphQL data source and caching layer for query results, subscriptions state, and rate limiting. |
| 45 | Integration | EV Charging | C++ | [EVerest](https://openeverest.io/) | EVerest is the open firmware stack for EV charging infrastructure (Linux Foundation Energy). Add Valkey for session caching, OCPP message queuing, and real-time charger state management. |

### CNCF Projects

| \# | Type | Track | Language | Project | Description |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 46 | Integration | Service Mesh | Go | [Istio](https://github.com/istio/istio) | CNCF Graduated. Service mesh for Kubernetes. Add Valkey for rate limiting state, external authorization cache, and telemetry buffering. |
| 47 | Integration | Application Runtime | Go | [Dapr](https://github.com/dapr/dapr) | CNCF Graduated. Distributed application runtime. Currently supports Redis as a state store, pub/sub, and binding — add native Valkey component. |
| 48 | Integration | API Gateway | Go | [Contour](https://github.com/projectcontour/contour) / [Emissary-Ingress](https://github.com/emissary-ingress/emissary) | CNCF projects. Add Valkey for rate limiting state and session affinity data. |
| 49 | Integration | GitOps | Go | [Argo CD](https://github.com/argoproj/argo-cd) | CNCF Graduated. Argo CD uses Redis for caching. Add native Valkey support as a drop-in replacement with enhanced cluster capabilities. |
| 50 | Integration | Artifact Registry | Go | [Harbor](https://github.com/goharbor/harbor) | CNCF Graduated. Cloud-native artifact registry. Currently uses Redis for caching and job queues — add native Valkey support. |
| 51 | Integration | Developer Portal | JavaScript | [Backstage](https://github.com/backstage/backstage) | CNCF Incubating. Open platform for building developer portals. Add Valkey for catalog caching, search indexing, and session management. |
| 52 | Integration | Serverless | Go | [Knative](https://github.com/knative/serving) | CNCF Incubating. Kubernetes-based platform for serverless workloads. Add Valkey for autoscaler state and request buffering. |
| 53 | Integration | Observability | Go | [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-demo) | CNCF Graduated. Add Valkey as a backend for trace/metric buffering and as a component in the OTel demo application. |
| 54 | Integration | Messaging | Go | [NATS](https://github.com/nats-io/nats-server) | CNCF Graduated. Connective technology for distributed systems. Add Valkey as a persistence layer for JetStream or as a KV store bridge. |
| 55 | Integration | Chaos Engineering | Go | [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) | CNCF Incubating. Add Valkey-specific chaos experiments (network partition, memory pressure, cluster failover testing). |
| 56 | Integration | Policy Engine | Go | [Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa) | CNCF Graduated. Add Valkey as a cache for policy decisions and external data source for real-time policy evaluation. |
| 57 | Integration | Cost Management | Go | [OpenCost](https://github.com/opencost/opencost) | CNCF Sandbox. Kubernetes cost monitoring. Add Valkey for caching cost allocation data and query results. |
| 58 | Integration | Service Mesh | Rust | [Linkerd](https://github.com/linkerd/linkerd2) | CNCF Graduated. Ultralight service mesh. Add Valkey for rate limiting state and distributed circuit breaker patterns. |

---

## Track B — Build an Application

| \# | Type | Track | Language | Project | Description |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 59 | New | Web Development | JavaScript | [Valkey.io Rewrite](https://github.com/valkey-io/valkey-io.github.io) | Transform the [valkey.io](http://valkey.io) website from [Zola](https://github.com/getzola/zola) to [Astro](https://github.com/withastro/astro) + [React](https://github.com/facebook/react) / [Svelte](https://github.com/sveltejs/svelte). Add interactivity to search anything from anywhere in the site. Include Static pages, Documentation, Blogs, Topics, Commands. |
| 60 | New | e-Commerce Demo | Any | [Valkey E-Commerce Demo](https://github.com/opensource-for-valkey/valkey-ecommerce-demo) | Build a complete e-commerce demo application showcasing Valkey for cart management, session storage, product catalog caching, real-time inventory, and search. |
| 61 | New | Gaming | JavaScript | Kahoot-like Quiz Game | Build a real-time multiplayer quiz game (Kahoot-style) using Valkey for game state, player scores, leaderboards, and pub/sub for live question broadcasting. |
| 62 | New | Gaming | Any | MMORPG | Build a Massively Multiplayer Online Role-Playing Game leveraging Valkey for player state, world state, inventory management, chat, and real-time combat calculations. |
| 63 | New | Gaming | JavaScript | Infinite Canvas Multiplayer (Slither.io) | Build an infinite canvas multiplayer game (like Slither.io) using Valkey for real-time player positions, collision detection, leaderboards, and pub/sub for state synchronization. |
| 64 | New | Kubernetes Demo | Any | [Voting App for Kubernetes](https://github.com/kodekloudhub/example-voting-app) | Fork and enhance the KodeKloud example voting app to use Valkey as the primary data store with [k8s-specifications](https://github.com/kodekloudhub/example-voting-app/tree/master/k8s-specifications). |
| 65 | New | Retail Demo | Any | [Retail Store Sample App](https://github.com/aws-containers/retail-store-sample-app) | Enhance the AWS containers retail store sample app with Valkey for caching, sessions, and real-time features. |
| 66 | New | AI/ML Demo | Python | [Valkey for AI](https://github.com/meet-bhagdev/valkeyforai) | Build or extend AI-powered applications showcasing Valkey's vector search, semantic caching, and agent memory capabilities. |
| 67 | New | UI Tool | JavaScript | [Valkey Admin](https://github.com/valkey-io/valkey-admin) | Enhance the Valkey Admin web-based administration tool with new features, improved UX, real-time metrics visualization. |
| 68 | New | UI Tool | JavaScript | [BetterDB Monitor](https://github.com/betterdb-inc/monitor) | Contribute to the BetterDB monitoring tool for Valkey clusters. |
| 69 | New | UI Tool | JavaScript | Valkey UI (Svelte) | Build a lean administration UI using [Svelte](https://github.com/sveltejs/svelte) — aligned with Valkey's low memory footprint and preference for compiled over Virtual DOM. |
| 70 | New | Developer Tool | Any | SQL to Valkey Command Translator | Build a utility that translates SQL queries to equivalent Valkey commands, enabling developers familiar with SQL to interact with Valkey data structures intuitively. |
| 71 | New | ORM / ODM Library | Python | Flask-Valkey né [Flask-Redis](https://github.com/underyx/flask-redis) | A Flask extension for Valkey with first-party support using [GLIDE](https://github.com/valkey-io/valkey-glide/) client. |
| 72 | New | Library | Python | [fastapi-cache](https://github.com/long2ice/fastapi-cache) | fastapi-cache caches FastAPI responses and function results. Add Valkey backend using [GLIDE](https://github.com/valkey-io/valkey-glide/) for Python. |
| 73 | New | Proxy / Library | Any | Open Source S3 Proxy Transparent Cache to Valkey | Create a transparent caching layer using the S3 API Protocol supporting [MinIO](https://github.com/minio/minio), [RustFS](https://github.com/rustfs/rustfs), [Ceph](https://github.com/ceph/ceph), [SeaweedFS](https://github.com/seaweedfs/seaweedfs). |
| 74 | New | Messaging / Queue Platform | Java | Valkey Kafka Connector | Build a Kafka Connect sink/source connector for Valkey enabling real-time cache updates from [Apache Kafka](https://github.com/apache/kafka) and [Redpanda](https://github.com/redpanda-data/redpanda) streams. |
| 75 | New | AI/ML Agentic | JavaScript | [OpenClaw](https://github.com/openclaw/openclaw) | OpenClaw is a personal AI assistant across multiple channels. Add Valkey for distributed semantic cache. |
| 76 | New | AI/ML Agentic | Go | [PicoClaw](https://github.com/sipeed/picoclaw) | PicoClaw is an ultra-lightweight personal AI Assistant in Go. Add Valkey for distributed semantic cache. |
| 77 | New | AI/ML Agentic | Python | [OpenViking](https://github.com/volcengine/OpenViking) | OpenViking is an open-source context database for AI Agents. Add Valkey for fast context retrieval and session management. |
| 78 | New | AI/ML Agentic | Python | [Strands Agents](https://github.com/strands-agents) | Build Valkey-powered tools and memory for Strands AI agents — from simple conversational assistants to complex autonomous workflows. |

---

## Other Application Ideas

These are additional application concepts that teams can build using Valkey:

- **Rate Limiter** — Distributed rate limiting service
- **URL Shortener** — High-performance URL shortening with analytics
- **Notification System** — Real-time push notification infrastructure
- **News Feed System** — Social media-style feed aggregation
- **Chat System** — Real-time messaging with presence and typing indicators
- **Search Autocomplete** — Type-ahead suggestion engine
- **Proximity Service** — Location-based nearby search
- **Nearby Friends** — Real-time friend location sharing
- **Distributed Message Queue** — Lightweight queue implementation on Valkey
- **Metrics Monitoring & Alerting** — Time-series metrics with threshold alerts
- **Ad Click Event Aggregation** — Real-time click counting and deduplication
- **Hotel Reservation System** — Inventory management with distributed locking
- **Real-time Gaming Leaderboard** — Sorted set-based live leaderboards
- **Payment System** — Idempotent payment processing with Valkey
- **Digital Wallet** — Balance management with atomic operations
- **Stock Exchange** — Order book matching engine
- **Matchmaking System** — Player skill-based matchmaking
- **Transparent Caching via CDC** — Write-through cache using [Debezium](https://github.com/debezium/debezium)
- **Consistent Hashing Library** — Client-side consistent hashing for Valkey

---

## Reference Samples

- [Bedrock Example with Strands](https://github.com/aws-samples/amazon-elasticache-samples/blob/main/navigator/backend/agent.py)
- [Spring Data Valkey](https://github.com/valkey-io/spring-data-valkey)
- [Django Valkey](https://github.com/django-commons/django-valkey)
- [Valkey GLIDE Client](https://github.com/valkey-io/valkey-glide/)
- [Valkey GLIDE for PHP](https://github.com/valkey-io/valkey-glide-php)
- [Valkey Vector Search](https://github.com/valkey-io/valkey-search)

---

## How to Participate

1. Review the projects above and pick one that matches your team's skills.
2. Form a team of 2–4 members.
3. Fork or create a repository on GitHub.
4. Build your integration or application during June 20 – July 5.
5. Submit a PR to the upstream project (Track A) or publish your application (Track B).
6. Present your work on June 21 at Amazon HYD13.

See the full hackathon details in the [README](./README.md).
