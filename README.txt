FIZZY WALLET - get your .apk (no coding, no Android Studio)
1. Make a free account on github.com, click New repository, name it fizzy-wallet.
2. Click "uploading an existing file" and drag EVERYTHING from this folder in (including the hidden .github folder), then Commit.
   If .github did not upload: Actions tab > "set up a workflow yourself" > paste the text of build-apk.yml > Commit.
3. Open the Actions tab, wait ~5-8 minutes for "Build APK" to turn green.
4. Open that run, scroll to Artifacts, download FizzyWallet-apk (a zip containing app-debug.apk).
5. Send app-debug.apk to your phone, allow "install unknown apps", tap it to install.
