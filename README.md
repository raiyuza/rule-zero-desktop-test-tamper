# Rule Zero desktop: test update feed

Test builds of the Rule Zero desktop app, used to develop and test its self-update (electron-updater, GitHub provider).
Not for players. Every installer has a detached Ed25519 signature (`.sig`) that the app checks before it installs an update.
