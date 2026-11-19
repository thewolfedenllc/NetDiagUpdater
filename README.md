# NetDiagUpdater

Update feed for NetDiagEssentials tester builds.

`update.json` is the feed the app reads at startup. It is signed with an Ed25519 key that stays offline; the app
carries only the public key and ignores any feed whose signature does not verify.

Installers are attached to Releases, not stored in this repository.

This repository contains no application source code. All rights reserved.
