# [bip324-mitm](https://github.com/RazorBest/bip324-mitm)
A Rust crate implementing the MitM adaptation of the BIP-324 encrypted protocol. Used for MitM proxies and network analysis tools.

I created a PR that handled writing the BIP324 protocol separately. This PR was merged. This task involved the following sub-tasks:
1.  Separating concerns between writing and reading. This involved separating the state machines.
2. Byte level granularity by introducing more buffers
3. Ensuring safe transitions in case of errors

- https://github.com/RazorBest/bip324-mitm/issues/5
- https://github.com/RazorBest/bip324-mitm/pull/10

# [bitcointranscripts - Bitcoin Dev Project](https://github.com/bitcointranscripts/bitcointranscripts)

A treasure trove of transcripts associated with Bitcoin and Lightning Network

I opened several PRs where I reviewed AI transcriptions from various Bitcoin technical podcasts and lectures. My work involved:
1. Checking for errors in technical terms and Bitcoin-related language. 
2. Ensuring coherent paragraphing around chapter titles and speaker timestamps.
3. Breaking the transcripts into manageable segments using my familiarity with the material.
4. Accurately attributing speakers, preventing potential mix-ups or merging of dialogue caused by AI transcription errors.

All the transcripts I reviewed are in production and can be viewed by clicking the titles.

- [Bitcoin and Privacy Under Attack: Tornado Cash, Samourai Wallet and Fixing the Great Consensus Cleanup](https://btctranscripts.com/bitcoin-explained/the-great-consensus-cleanup-revival) - https://github.com/bitcointranscripts/bitcointranscripts/pull/653
- [From Network Topology to Watchtowers: Sergi Delgado on Adversarial Research in Bitcoin and Lightning](https://btctranscripts.com/chaincode-podcast/watchtowers-lightning-privacy) - https://github.com/bitcointranscripts/bitcointranscripts/pull/652
- [Bitcoin Core 26.0: What's New, Plus F2Pool's OFAC Transaction Filtering](https://github.com/bitcointranscripts/bitcointranscripts/pull/655)

# [Arkade](https://github.com/arkade-os)
A programmable execution layer for Bitcoin. It enables fast, self-custodial financial applications on Bitcoin, including lending, smart wallets, and trading, without changing the protocol or requiring trusted intermediaries.

I am currently working to provide Rust alternatives to the [SDK demos for Arkade](https://github.com/arkade-os/demos) - https://github.com/arkade-os/demos/issues/2

- https://github.com/arkade-os/demos/pull/3
- https://github.com/arkade-os/demos/pull/4

