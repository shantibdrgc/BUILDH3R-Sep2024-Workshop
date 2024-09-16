# Discord Use Case

## zkMIPS for Decentralized Identity Verification (KYC)

### Problem
To comply with KYC (Know Your Customer) and AML (Anti-Money Laundering) regulations, companies often need to verify users’ identities. However, exposing full identity information creates privacy risks and potential misuse of personal data.

### Solution: zkMIPS-Based Private Identity Verification
With zkMIPS, companies can implement a KYC solution that proves users’ identities have been verified without revealing their personal information. This allows decentralized platforms to comply with KYC/AML regulations while maintaining user privacy.

- User Identity Proofing:
    Users submit their identity information (e.g., government ID) to a zkMIPS program, which generates a proof that:
        - Confirms the user’s identity is valid and verified.
        - Ensures compliance with KYC regulations.
        - Does not reveal any specific identity data (e.g., name, address, or ID number).

- Proof Submission:
    The zkMIPS proof is submitted to an on-chain verifier, which:
        - Confirms the user’s identity has been verified.
        - Proves the platform complies with KYC/AML regulations.
- Access to Services:
    Users can access decentralized financial services or other platforms that require KYC verification without disclosing their personal information to the platform itself.

### Why zkMIPS for KYC Verification?
- Privacy: Users’ personal identity information remains confidential.
- Compliance: zkMIPS ensures compliance with KYC/AML regulations without exposing sensitive details.
- Decentralization: Enables decentralized platforms to implement KYC in a privacy-preserving way.

### Solution Components
- zkMIPS: Generates cryptographic proofs verifying the validity of identity without revealing personal data.
- Smart Contract: Verifies the KYC proof on-chain.
- Golang & Rust: Used to build the zkMIPS identity verification modules.
