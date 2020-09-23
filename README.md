Examples related to ethereum layer 2. ([Home](..))

This document contains info about:
- [Ethereum Concepts](#ethereum-concepts)
- [Explorers](#explorers)


# Layer2 Concepts

| Plasma         | 
| -----------    | ------------
| [hub_plasma]
| [minviable]
| [whatisplasma]
| [learnplasma]

[hub_plasma]: https://docs.ethhub.io/ethereum-roadmap/layer-2-scaling/plasma/
[minviable]:    https://ethresear.ch/t/minimal-viable-plasma/426
[whatisplasma]: https://docs.omg.network/faq#what-is-plasma
[learnplasma]:  https://www.learnplasma.org/en/

# Layer2 Solutions

| Level 2 solutions | Website           | Docu                 |   Github           | Explorer      | Web Wallet      | Technology
| ---------------   | ----------------  | ---------------      | ---------------    |----------     | -----------     | -----------
| ZoKrates          |                   | [zokrates_docs]      | [zokrates_gh]      |               |                 | toolbox for zkSNARKs
| Optimism          | [optimism]        | [optimism_docs]      | [optimism_gh]      |               |                 | Optimistic Virtual Machine (EVM compatible) L1<->L2 not yet implemented
| Matic             | [matic]           | [matic_docs]         | [matic_gh]         | [matic_exp]   |                 | Plasma & PoS checkpoints on ETH (EVM compatible)
| Loom              | [loomx]           | [loomx_docs]         | [loomx_gh]         | [loomx_exp]   | [loomx_wallet]  | DPoS side chain (erc20/erc721 transfer) (EVM compatible)
| Omg (was OmiseGO) | [omg]             | [omg_docs]           | [omg_gh]           | [omg_exp]     | [omg_wallet]    | Plasma / ETH & ERC20 (utxo)
| zksync            | [zksync]          | [zksync_docs]        | [zksync_gh]        | [zksync_exp]  | [zksync_wallet] | Zkrollup ERC20 (only listed tokens) (rinkeby, ropsten) smart contracts via Zinc


[zokrates]:         https://github.com/Zokrates/ZoKrates
[zokrates_docs]:    https://zokrates.github.io/

[optimism]:         https://optimism.io/
[optimism_docs]:    https://docs.optimism.io/
[optimism_gh]:      https://github.com/ethereum-optimism/optimism-monorepo

[matic]:            https://matic.network/
[matic_gh]:         https://github.com/maticnetwork
[matic_docs]:       https://docs.matic.network/
[matic_exp]:        https://explorer.matic.network/txs

[loomx]:            https://loomx.io
[loomx_gh]:         https://github.com/loomnetwork
[loomx_docs]:       https://loomx.io/developers
[loomx_exp]:        https://basechain-blockexplorer.dappchains.com/
[loomx_wallet]:     https://wallet.loomx.io

[omg]:          https://omg.network/
[omg_gh]:       https://github.com/omgnetwork
[omg_docs]:     https://docs.omg.network/
[omg_exp]:      https://blockexplorer.ropsten.v1.omg.network
[omg_wallet]:   https://webwallet.ropsten.v1.omg.network/

[zksync]:       https://zksync.io/
[zksync_docs]:  https://zksync.io/faq/intro.html
[zksync_gh]:    https://github.com/matter-labs/zksync
[zksync_exp]:   https://rinkeby.zkscan.io/explorer
[zksync_wallet]: https://rinkeby.zksync.io/






# Zero Knowledge

| ZK Proofs               | Examples         | Languages
|------------------       | ---------------- | ------
| [zkproofs]              | [alibaba]        | [zinc]
| [zkp]                   | [waldo1]
| [snark]                 | [waldo2]
| [bulletproof1]
| [bulletproof2]

[zkproofs]:     https://github.com/matter-labs/awesome-zero-knowledge-proofs
[zkp]:            https://zkp.science/
[snark]:        https://z.cash/technology/zksnarks/
[bulletproof1]: https://web.stanford.edu/~buenz/pubs/bulletproofs.pdf
[bulletproof2]:    https://crypto.stanford.edu/bulletproofs/

[alibaba]:         https://en.wikipedia.org/wiki/Zero-knowledge_proof#The_Ali_Baba_cave
[waldo1]:         http://www.wisdom.weizmann.ac.il/~naor/PAPERS/waldo.pdf
[waldo2]:         https://medium.com/swlh/a-zero-knowledge-proof-for-wheres-wally-930c21e55399


[zinc]: https://zinc.matterlabs.dev/


| Abbreviations        | Meaning
|----------------   | ------------------
| ZK                | Zero-Knowledge
| Succinct            | Short and to the point / verifiable in short time  (requires trusted setup)
| Non-interactive   | One message (so no need for multiple rounds)
| SNARK                | Succinct Non-interactive adaptive ARgument of Knowledge 
| Argument            | Proof
| Transparent        | No trusted setup
| STARK             | Scalable Transparent ARguments of Knowledge (quantum-resistant)
| Bulletproef        | Short non-interactive zero-knowledge proofs that require no trusted setup  (range proofs) (not quantum-resistant)
