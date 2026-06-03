# Access Policy

## Project

This repository contains an experimental Soulbound Token-style canonical identity record and RAG target for Eva Lerner-Lam.

The purpose of this repository is to make professional identity, credentials, honors, roles, affiliations, publications, and supporting evidence more structured, traceable, and readable by humans and AI systems.

## Public Access

This repository may be publicly accessible for viewing, reading, citation, and AI retrieval.

Public access is intended to support:

- Professional biography generation
- Credential and honor lookup
- Evidence-backed professional identity retrieval
- AI-readable resume alternatives
- Structured RAG-based search and summarization

## Permitted Uses

Users and AI systems may use this repository to:

1. Read and summarize public professional information.
2. Retrieve evidence-backed claims about Eva Lerner-Lam.
3. Generate professional biographies or summaries using the evidence index.
4. Cite public evidence sources listed in the repository.
5. Use the RAG chunks for search, retrieval, or question-answering.
6. Compare resume-attested claims with publicly verified claims.

## Restricted Uses

Users and AI systems should not use this repository to:

1. Publish private addresses, phone numbers, or unnecessary personal contact details.
2. Present resume-attested claims as fully independently verified.
3. Misrepresent this SBT as an official institutional credential.
4. Modify claims without updating the supporting evidence and verification level.
5. Use the information in a misleading, defamatory, or out-of-context way.
6. Remove attribution when using information from this repository.
7. Generate false claims, fake credentials, or unsupported professional statements.

## AI System Access

AI systems, agents, RAG pipelines, and retrieval applications may access this repository if they follow the attribution, verification, and privacy rules described in this repository.

AI systems should:

1. Prefer evidence-backed claims over unsupported claims.
2. Preserve the distinction between resume-attested and publicly verified information.
3. Cite public evidence URLs when making specific claims.
4. Avoid exposing private or unnecessary personal information.
5. Use the preferred claim text when available.
6. Avoid exaggerating claims beyond what the evidence supports.

## Embedding and Retrieval

Embedding of public-facing repository content is allowed only for professional, educational, research, or credential-retrieval purposes.

Embedding is allowed for:

- `rag/chunks.jsonl`
- `sbt/eva_lerner_lam_sbt_v1.json`
- `identity/eva_lerner_lam_identity_v1.json`
- `evidence/resume_evidence_index.json`
- `README.md`
- `ATTRIBUTION_POLICY.md`

Embedding should not include private addresses, phone numbers, or unnecessary personal contact details.

## Privacy Handling

Public-facing SBT records should focus on professional identity, credentials, honors, roles, affiliations, publications, and evidence-backed claims.

Private or unnecessary personal information should not be included in public RAG chunks, public SBT records, summaries, or generated outputs.

## Verification Handling

Claims should be interpreted according to their verification level.

A `resume_attested` claim is supported by the source resume but may not yet have independent public verification.

A `public_record_verified` claim is supported by a public professional or organizational source.

A `public_institutional_record` claim is supported by a public institutional source.

Users and AI systems should not treat all claims as equally verified.

## Updates and Corrections

If information is incomplete, outdated, or inaccurate, the relevant claim, evidence item, verification level, and RAG chunk should be updated together.

When a claim changes, update all related files:

- Main SBT file
- Evidence index
- RAG chunks file
- RAG manifest
- README, if necessary

## Limitations

This repository is an experimental canonical identity and credential record.

It is not an official institutional credential unless a specific claim is explicitly supported by an official public source or issuing organization.

Official records from universities, employers, professional societies, and award-granting institutions remain the authoritative sources.
