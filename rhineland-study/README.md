# Rhineland Study MRI Protocols

The native Rhineland study MRI protocol, which runs on a MAGNETOM Prisma scanner (Siemens Healthineers, Erlangen, Germany), requires both "product" and "custom" sequence and image reconstruction software. The same applies for the adapted protocols compatible with "weaker" gradient systems. The native and compatible protocols provided here are using the "Rhineland Study MR Pulse Sequence and Protocol Package" (native: version 1.0; compatible: version 1.2), which also includes importable protocol formats (exar1 and pro). It is accessible via the [Siemens TeamPlay platform](https://webclient.us.api.teamplay.siemens-healthineers.com/c2p).

## NATIVE

### DZNE_RLS_v1p0_rhineland_3TPrisma (EN)

Rhineland study core protocol optimized for MAGNETOM Prisma.

### DZNE_RLS_v1p0_rhineland_3TPrisma_T2_HippocampalSubfields (DE)

Prisma-optimized free protocol for high-resolution Hippocampal subfields T2-weighted imaging (based on Siemens "product" sequence).

## COMPATIBLE

Corresponding protocol compatible with "weaker" MRI gradient systems.

Note: depending on the scanner type, different settings may apply sporadically (e.g. gradient mode "performance" on Prisma vs. "fast" on Skyra). This is done to match the timing parameters across different scanners.

### DZNE_RLS_v1p2_compatibility_3TPrisma (EN/DE)

Adjusted for MAGNETOM Prisma.

### DZNE_RLS_v1p2_compatibility_3TSkyra (EN)

Adjusted for MAGNETOM Skyra.

## Acknowledgements:

Many thanks to:
- Rüdiger Stirnberg for first set up this repo and continuous development of his 3D-EPI branches.
- Desmond Tse for import validation and providing protocol printouts in English language.
- Falk Lüsebrink and Peter Dechent for import validation and providing protocol printouts in German language.
- Sascha Brunheim for keeping track and creating different protocol versions.
