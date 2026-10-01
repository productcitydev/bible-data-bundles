# Bible Data Bundles

Downloadable, on-device data bundles for the Bible app (web + mobile). Each release contains
standalone SQLite files for a given feature — clients download once and query locally, no
live backend database required for these lookups.

See `manifest.json` in each release for version, file size, and SHA-256 checksum per bundle.

## Bundles

- **cross-reference** — Theme, Person, Event, Word/Phrase, and Parallel verse connections,
  plus published (human-reviewed) Direct Quotation / Prophecy-Fulfillment / Theological
  Concept entries. Sourced from Nave's/Torrey's Topical Bible, STEPBible, Theographic Bible
  Metadata, and OpenBible.info — see the main app repo for full research/licensing docs.
- **lexicon** — Hebrew (BDB, via OpenScriptures) and Greek (Abbott-Smith, via STEPBible)
  word definitions, keyed by Strong's number.

Source/build scripts live in the main (private) application repository.
