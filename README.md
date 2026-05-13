## Open Source Contributions

**Redisson** - Java client for Redis/Valkey [24k+ ⭐]

- **v4.3.1** - Detected & fixed silent Redis Cluster topology refresh failure on k8s with critical production impact — https://github.com/redisson/redisson/pull/6993
- **v4.4.0** — https://github.com/redisson/redisson/releases/tag/redisson-4.4.0
  - Feature: Collection field index support for `RLiveObject` — https://github.com/redisson/redisson/pull/7106
  - Detected & fixed `RReadWriteLock` cross-instance zombie renewal causing lock contention, blocking write lock acquisition, reduced from 25,135ms to 93ms (~270× faster) — https://github.com/redisson/redisson/pull/7098
  - Detected & fixed `RedisNodeNotFoundException` in cluster mode due to incorrect slot calculation for `RRemoteService` and `RExecutorService` — https://github.com/redisson/redisson/pull/7027
  - Fixed `RMap.copy()` CROSSSLOT failure in Redis cluster mode — https://github.com/redisson/redisson/pull/7110
  - Fixed `RLiveObject.findIds()` throwing `StringIndexOutOfBoundsException` — https://github.com/redisson/redisson/pull/7103

**Cognee** — Knowledge graph & AI memory framework

- Identify & report Cypher search crash — https://github.com/topoteretes/cognee/pull/1725 [17k+ ⭐]
- Fix Memgraph batch edge insertion — https://github.com/topoteretes/cognee-community/pull/49 [47+ ⭐]
