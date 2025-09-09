<img src="RZ_logo.png" width="200">

# Security Auditing Summary: zero-knowledge Virtual Machine (zkVM)
This document provides a high-level summary of external security auditing and assessment of the RISC Zero zero-knowledge Virtual Machine (zkVM) protocol and implementation.

## Product Overview:
The RISC Zero [zero-knowledge virtual machine (zkVM)](https://dev.risczero.com/api/next/zkvm/) lets you prove correct execution of arbitrary Rust code. By allowing users to build zero-knowledge applications that leverage existing Rust packages, the RISC Zero zkVM makes it quick and easy to build powerful verifiable software applications. 

## Audit Log

| Start | Completed | Audit Firm | Audit Report |
|-------|-----------|------------|---------------|
| 2023-08-22 | 2023-10-26 | [Hexens](#about-hexens) | [zkVM](zkVM/hexens_zkVM_20231031.pdf) |
| 2023-11 | 2024-01 | [Hexens](#about-hexens) | [Circuit](circuits/hexens_v1c_stark2snark_20240520.pdf)|
| 2024-02 | 2024-03 | [Hexens](#about-hexens) | [Stark2Snark Circuit](circuits/hexens_v1c_stark2snark_20240520.pdf)|
| 2024-05 | 2024-06 | [Hexens](#about-hexens) | [SNARK Verifier Contract](contracts/hexens_verifiercontract_20240605.pdf) |
| 2024-08 | 2024-09 | [Veridise](#about-veridise) | [Solana Verifier SNARK Contract](contracts/veridise_solanaverifier_20240904.pdf) |
| 2024-09 | 2024-09 | [Veridise](#about-veridise) | [blobstream zero](blobstream/veridise-blobstream-20240909.pdf)
| 2024-09 | 2024-10 | [Veridise](#about-veridise) | [steel](steel/veridise_steel_20241007.pdf) |
| 2025-01 | 2025-02 | [Veridise](#about-veridise) | [Kailua](kailua/veridise-kailua-20250217.pdf) |
| 2024-06 | 2024-12 | [Veridise](#about-veridise) | [zkVM](zkVM/veridise_zkVM_20250224.pdf) |
| 2024-12 | 2024-12 | [Veridise](#about-veridise) | [bigint2 precompile](precompiles/veridise_bigint2_240324.pdf) |
| 2025-01 | 2025-02 | [Veridise](#about-veridise) | [keccak precompile](precompiles/veridise_keccak-250221.pdf) |
| 2025-02 | 2025-03 | [zkSecurity](#about-zkSecurity) | [solana groth16 verifier](groth16/zksecurity_groth16.pdf) |
| 2025-03 | 2025-04 | [Veridise](#about-veridise) |[boundless](boundless/veridise-boundless-250404.pdf) |
| 2025-07 | 2025-08 | [Hexens](#about-hexens) |[PoVW](povw/hexens-250827.pdf) |


## Appendix A: Audit Firm Details

### About Veridise
[Veridise](https://veridise.com) was founded in 2021 by a team of world-class academics.

The birthplace of Veridise is the UToPiA research group.

Our co-founder and UT Austin professor, Isil Dillig, leads the UToPiA research group, which focuses on program analysis, verification, and synthesis—an area of Computer Science that has profound implications for software security.

Starting in 2018, program analysis for smart contracts emerged as a central area of research for the group: They created advanced vulnerability detection tools and built deep domain expertise in the DeFi space.

The work of the group didn’t go unnoticed. Several security companies lined up to use these techniques, while protocols sought our expertise for audits.

These signals prompted us to roll up our sleeves and start Veridise.

Audit points of contact:
* Jon Stephens

Many Veridise team members, such as Kostas Ferles, Ben Sepanski, Shankara Pailoor, Ben Mariano, and Jacob Van Geffen previously worked as researchers in the UToPiA group, and many of them contributed to smart contract security research before joining Veridise. As a result, we are in the unique position of combining the latest academic research discoveries with deep industry experience for industry-leading audits.

Today, Veridise is lead by President & Co-founder Isil Dillig and CEO & Co-founder Jon Stephens. The Veridise team consists of 35+ dedicated professionals, continuing to advance blockchain security.

### About Hexens
[Hexens](https://hexens.io) is a cybersecurity company that strives to elevate the standards of security in Web 3.0, create a safer environment for users, and ensure mass Web 3.0 adoption.

Hexens has multiple top-notch auditing teams specialized in different fields of information security, showing extreme performance in the most challenging and technically complex tasks, including but not limited to: Infrastructure Audits, Zero Knowledge Proofs / Novel Cryptography, DeFi and NFTs. Hexens not only uses widely known methodologies and flows, but focuses on discovering and introducing new ones on a day-to-day basis.*

Audit points of contact: 
* Vahe Karapetyan <v.k@hexens.io> 
* Konstantin Andriotis <k.a@hexens.io>

### About zkSecurity
[zkSecurity](https://www.zksecurity.xyz/) specializes in advanced cryptographic solutions, including ZKP, MPC, FHE, and Post-Quantum Cryptography. We are committed to making your systems secure and future-proof.

Audit points of contact:
* David Wong <david@zksecurity.xyz>
