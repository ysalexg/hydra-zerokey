# Changed files
-----------------
.env
.gitignore
fork.md
src/locales/es/translation.json
src/main/services/download/download-manager.ts
src/main/services/game-files-manager.ts
src/main/services/notifications/index.ts
src/preload/index.ts
src/renderer/src/declaration.d.ts
src/renderer/src/pages/downloads/download-group.tsx
src/renderer/src/pages/downloads/downloads.tsx
src/types/download.types.ts

# Build
-----------------
yarn build; yarn electron-builder
copy python rpc to resources
copy zerokey to resources

# Sync with upstream
-----------------
git fetch upstream -> downloads changes
git checkout main
git merge upstream/main -> merge changes
git push origin main

# Succesful
-----------------
Deltarune ✔️
Cuphead ✔️
Lethal Company ✔️
Hollow Knight Silksong ✔️
Resident Evil 2 ✔️ -> coldclient failed, used goldberg
The Witcher 3 ✔️
Ultrakill ✔️

# Failed
-----------------
Days Gone ❌ -> weird directories, appid not found, manifest not found