# libsecret

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libsecret.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libsecret-0.21.7-h1e2da66_0.conda | `2f4c634536ee8bccfb9f57b0248ef754d2ad4daa587673b76277cd515a2cbf1c` | conda-forge libsecret 0.21.7 h1e2da66_0 (LGPL-2.1-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name libsecret \
    --version 0.21.7 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libsecret-0.21.7-h1e2da66_0.conda#2f4c634536ee8bccfb9f57b0248ef754d2ad4daa587673b76277cd515a2cbf1c \
    --require lib/libsecret-1.so.0
```

