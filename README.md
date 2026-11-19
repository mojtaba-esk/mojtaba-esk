# Hi, I'm Mojtaba

**Senior backend engineer** working in Go, distributed systems and blockchain infrastructure.

I build the systems around blockchain protocols: test-orchestration frameworks, e2e and conformance suites, indexers and RPC services. 100+ merged PRs across Celestia, Sei and the Cosmos ecosystem. Based in Germany, working remotely.

---

## What I've built

| Project | What it is |
|---|---|
| [**Knuu**](https://github.com/celestiaorg/knuu) | Kubernetes-native framework for orchestrating test infrastructure. Used to run Celestia network e2e tests. |
| [**Tastora**](https://github.com/celestiaorg/tastora) | Docker-based framework for provisioning chains and nodes in e2e tests: volume lifecycle, node types, upgrade scenarios. |
| [**Talis**](https://github.com/celestiaorg/talis) | Infrastructure provisioning service with a Go client: projects, tasks and instances, parallel instance creation via worker pool. |
| [**Cosmologger**](https://github.com/celestiaorg/cosmologger) | Listens to NewBlock and Tx events of Cosmos-based chains and stores them in PostgreSQL for analysis. Later forked into Celestia and customized. |

## Contributions to production chains

**[Sei](https://github.com/sei-protocol/sei-chain)**
- EVM RPC conformance suite: spec-fixture integration tests with blocking CI.
- Ethereum-parity fixes in `evmrpc`: `eth_call` with EIP-1559, `eth_getLogs` range validation, block transaction count consistency, genesis block handling, unknown block hash behavior.
- Legacy RPC deprecation and HTTP batch handling; node `init`/config fixes and embedded genesis for well-known chains.

**[Celestia](https://github.com/celestiaorg/celestia-app)**
- e2e and upgrade test suites: v5 to v6 upgrade, state sync after app version upgrades, minor-version compatibility, IBC PFM multihop, validator liveness checks.
- Reliability work on nightly and state-sync tests.

## Personal Go projects

Both started as engineering exercises and I kept them because I liked how they turned out.

- [**sandbox-control-plane**](https://github.com/mojtaba-esk/sandbox-control-plane): multi-tenant sandbox API with OAuth (Ory Hydra) and JWT, project membership, plan quotas, and Redis rate limiting. Includes load tests and a written scaling roadmap.
- [**mempool-mini**](https://github.com/mojtaba-esk/mempool-mini): transaction mempool with fee-priority ordering, gas/count limits, interval block production, REST API and a CLI. Includes 100K-transaction performance tests.

## Stack

Go · distributed systems · Kubernetes · Docker · PostgreSQL · Redis · REST and RPC APIs · EVM RPC · Cosmos SDK / IBC · CI pipelines

Currently exploring: agent-based systems

## Contact

[LinkedIn](https://www.linkedin.com/in/mojtaba-eskandari/)
