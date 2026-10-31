# Offline translation models — continuity handoff

Last updated: 2026-10-31

## Purpose
Public supporting repository for offline translation model archives used by the private RussSearchOPPO Android app.

## README-recorded state
- Model pairs: ru-en, en-ru, zh-en, en-zh.
- Russian↔Chinese translation is composed through English: ru→en→zh and zh→en→ru.
- README lists SHA-256 values for each archive and describes Helsinki-NLP Opus-MT / CC-BY-4.0 provenance.
- README says archives had not yet been uploaded to release `translation-models-v1`; owner upload was pending at the time of that note.
- The private app repo contains the integration/workflow documentation at `docs/hive/WHERE-IS-WHAT.md`.

## Immediate next steps
1. Check whether release `translation-models-v1` now exists and whether all four archives are attached.
2. Verify each downloaded archive against the SHA-256 recorded in the repository manifest.
3. Confirm app-side model download, extraction, storage and inference on the target OPPO device.
4. Update release status and checksums only after verifying actual artifacts.
5. Preserve license attribution and model provenance.

## Safety
- Do not commit API keys or private user data.
- Treat README checksums as expected values until independently verified against the actual downloadable archives.

## Change record
- 2026-10-31: Added this continuation handoff on a documentation-only branch.
