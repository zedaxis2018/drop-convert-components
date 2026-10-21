# Drop Convert component packs

Optional packs downloaded by the Drop Convert installer when the matching component is ticked.
They are unmodified third-party redistributables, repackaged into zips that unpack straight into the
Drop Convert folder. Each release matches a Drop Convert version; `manifest.json` lists file names,
sizes and SHA-256 hashes, which the installer verifies before extracting.

| Pack | Contents | Licence |
| --- | --- | --- |
| ffmpeg | ffmpeg 9 essentials build from gyan.dev | GPL v3 |
| libreoffice | LibreOffice 26.8.1 program files, pruned for headless conversion (no help, no dictionaries, English resources only) | MPL 2.0 / LGPL v3 |
| cadkernel | OpenCascade 7.9 Python bindings (cadquery-ocp 8.0.1) with VTK 9.6 | LGPL v2.1 (OCCT), BSD (VTK), Apache 2.0 (OCP) |

The application itself lives in a separate private repository.
