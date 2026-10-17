# MrMR

A macOS app for reading Markdown and reviewing changes in git repositories.

**Website: [mr-gera.github.io/mrmr-releases](https://mr-gera.github.io/mrmr-releases/)** — features, screenshots, in English and Ukrainian.

## Download

**[Download MrMR 1.1.0 (pre-release)](https://github.com/mr-gera/mrmr-releases/releases/download/v1.1.0/MrMR.dmg)**

All versions: [Releases](https://github.com/mr-gera/mrmr-releases/releases)

## Install

1. Open the `.dmg` and drag **MrMR** to **Applications**.
2. Optional: the `mrmr` command-line tool is inside the app:

   ```
   ln -s /Applications/MrMR.app/Contents/Resources/mrmr /usr/local/bin/mrmr
   ```

Pre-release builds are not notarized yet. If macOS blocks the first launch, open
System Settings → Privacy & Security and click **Open Anyway**, or run:

```
xattr -dr com.apple.quarantine /Applications/MrMR.app
```
