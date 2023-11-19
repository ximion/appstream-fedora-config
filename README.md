# AppStream Fedora Config

Example for building Fedora AppStream metadata using appstream-generator

Run like this:
```bash
cd /path/to/this/repository
FEDORA_VERSION=40
appstream-generator run $FEDORA_VERSION
```

or

```bash
FEDORA_VERSION=40
appstream-generator -w /path/to/this/repository run $FEDORA_VERSION
```
