# Yudrab pour Mac et Windows — releases

Ce dépôt ne contient que les **releases** de l'app de bureau Yudrab. Le code source est dans le dépôt
privé `yudrab/yudrab-apps` (`apps/desktop`).

- **Télécharger** : [dernière release](https://github.com/yudrab/desktop-releases/releases/latest) —
  `Yudrab-mac-arm64.dmg` (Mac Apple Silicon), `Yudrab-mac-x64.dmg` (Mac Intel),
  `Yudrab-windows-x64.exe` (Windows).
- **Mise à jour automatique** : l'app installée lit les releases d'ici, sans jeton, et se met à jour
  toute seule.
- **Publication** : uniquement par le workflow `desktop-release.yml` de `yudrab/yudrab-apps`, sur un tag
  `desktop-vX.Y.Z`. Ne rien publier à la main.
