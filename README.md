# hwik-chain-data

Copies of the hwik engine's creation store: the pool creation logs and read position it has read from GIWA Sepolia, all public chain events.

An engine uses a copy only when its sha256 matches the one pinned in its deployment, and only to seed an empty store. Copies are published as release assets and refreshed when a venue is added.
