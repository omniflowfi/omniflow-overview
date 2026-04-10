# Omniflow

**Bridging before depositing is broken.**

Today:
Bridge → wait → switch chain → deposit

With Omniflow:
Deposit → done

Omniflow lets any protocol accept liquidity from any chain
in a single transaction.

No bridge step. No fragmented pools.
Built on LayerZero V2.

---

## The problem

Liquidity in DeFi is fragmented across chains.

To use a protocol on another chain, users must:

1. bridge their assets
2. wait for confirmation
3. switch networks
4. then interact with the protocol

This creates:

* unnecessary friction
* slow execution
* capital inefficiency
* duplicated liquidity across chains

As the number of chains grows, this UX breaks down further.

---

## The shift

Users shouldn’t move between chains.

**Execution should.**

Omniflow removes the need for users to bridge assets manually
by moving execution across chains instead.

---

## The solution

Omniflow turns cross-chain deposits into a single action.

A user can:

* deposit from any chain
* trigger execution on a destination chain
* complete the full flow in one transaction

No intermediate steps. No manual bridging.

---

## How it works

1. A user submits a transaction on the source chain
2. Omniflow uses LayerZero V2 messaging (`lzCompose`)
3. Execution is triggered on the destination chain
4. Liquidity is settled directly in the target pool

The entire flow is handled atomically from the user’s perspective.

---

## What Omniflow is

Omniflow is **not**:

* a bridge
* a DEX

It is a **liquidity coordination layer**.

Instead of moving users between chains,
Omniflow moves execution and liquidity across them.

---

## What this enables

* Cross-chain deposits in one transaction
* Unified liquidity instead of per-chain silos
* Simpler user experience
* New primitives for omnichain DeFi

---

## Testnet

Omniflow is live on testnet.

The current version demonstrates:

* single-transaction cross-chain deposits
* execution on a destination chain
* end-to-end flows powered by LayerZero V2 (`lzCompose`)

👉 https://testnet.omniflow.fi

---

## For builders

Omniflow acts as a base layer for omnichain applications.

Protocols can integrate Omniflow to:

* accept liquidity from any chain
* remove bridge friction from their UX
* avoid fragmented liquidity pools

Integration examples and documentation are coming next.

---

## Tech

* LayerZero V2
* OFT (Omnichain Fungible Token)
* `lzCompose` cross-chain execution

---

## Status

Active development.

The protocol is being iterated across multiple testnets
with a focus on stabilizing core omnichain primitives.

---

## Contact

For technical walkthroughs, partnerships, or early access:

* GitHub: https://github.com/omniflowfi
* Website: https://omniflow.fi
