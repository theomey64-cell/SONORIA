# SONOR V9 — Neon Session

Nouvelle direction artistique violet nocturne, animations d'ambiance, particules, vinyle, cartes interactives, indicateur de progression des manches, écrans de jeu modernisés et accessibilité mouvement réduit.

## Déployer sur Render
- Dépôt GitHub avec `package.json`, `server.js` et `public/` à la racine.
- Runtime: Node
- Build Command: `npm install`
- Start Command: `npm start`
- Branch: la branche existante du dépôt (`main` ou `master`).

## Local
`npm install` puis `npm start` et ouvrir `http://localhost:3000`.

## Remarques
Le jeu reste basé sur Socket.IO. Les salons en mémoire ne survivent pas à un redémarrage. La lecture YouTube peut être bloquée par certaines restrictions navigateur ou vidéo. La musique d'ambiance s'active après interaction de l'utilisateur.


V10: interface en français, anglais, espagnol et chinois simplifié. Sélecteur de langue dans l’en-tête; préférence enregistrée dans le navigateur. Les situations écrites par les joueurs et les vidéos YouTube ne sont pas traduites automatiquement.
