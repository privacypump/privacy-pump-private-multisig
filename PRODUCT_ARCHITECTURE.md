# Private Multisig architecture

Private Multisig is the multi-member Privacy Pump product. The shared Private Vault program stores threshold, counts, signer commitment root/version, and proposal state without a public member list.

Members receive wallet-scoped encrypted access material through a private service boundary. That delivery metadata does not authorize actions. Arcium-backed receipts and on-chain root/version checks authorize proposal actions. Member changes are proposals that atomically advance member count, threshold where needed, root, and version.

No production frontend, relayer, access service, database, or signer storage is published here.
