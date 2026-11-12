# Amethyst Linux — package mirror

APT repository for **Amethyst Linux** (Debian testing rolling, desktop-only,
GNOME 3 Revitalized). Packages are served over HTTPS from this static tree.

## Using the repository

```
Types: deb
URIs: https://<user>.github.io/amethyst-archive/
Suites: amethyst
Components: main
Signed-By: /usr/share/keyrings/amethyst-archive-keyring.gpg
```

The archive keyring is `amethyst-archive-keyring.gpg` at this site root.

## Integrity

`dists/amethyst/InRelease` is signed by the Amethyst Release key; every
client verifies it against the shipped keyring. This site is static content
— no upload access is involved.
