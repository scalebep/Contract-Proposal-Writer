# Contract & Proposal Writer

A Claude Code skill that drafts business documents with jurisdiction-aware
clauses for the US (Delaware), EU, UK and DACH:

- contracts
- proposals
- statements of work (SOWs)
- NDAs
- master service agreements (MSAs)
- GDPR data processing addenda

It is packaged here as a Claude Code plugin.

## Source and licence

Copied from
[borghei/Claude-Skills](https://github.com/borghei/Claude-Skills/tree/main/business-growth/contract-and-proposal-writer)
by Amin Borghei, under the MIT licence with the Commons Clause (see `LICENSE`).
It may be used, modified and shared, including for internal business use, but
not sold or offered as a paid product or service.

## Use

Ask for what you need, for example "draft a fixed-price contract for a website
build" or "write a proposal for this client".

The skill also includes three Python scripts in
`skills/contract-and-proposal-writer/scripts/`:

- a clause checker
- a contract version comparison
- a proposal cost estimator

They only read local files.

These are templates, not legal advice. Have a lawyer review anything high-value
or complex.
