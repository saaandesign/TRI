# Prépa — calendrier d'entraînement

Appli web statique (aucune installation, aucun serveur) : calendrier semaine / mois, pastilles par discipline
(CAP, vélo, natation, renfo), compteur de semaines et jours avant la course, dates et séances modifiables au clic.

## Mettre en ligne avec GitHub Pages
1. Crée un dépôt GitHub (par ex. `prepa`) et envoie-y tous les fichiers de ce dossier à la racine.
2. Dépôt → **Settings → Pages** → *Build and deployment* : **Deploy from a branch**, branche `main`, dossier `/ (root)` → Save.
3. Après 1-2 minutes : `https://<ton-pseudo>.github.io/prepa/`

## Sur le téléphone
- iPhone (Safari) : Partager → **Sur l'écran d'accueil**.
- Android (Chrome) : menu ⋮ → **Installer l'application** / **Ajouter à l'écran d'accueil**.

## Tes données
Les modifications sont enregistrées **sur l'appareil** (navigateur). Menu → *Exporter* crée une sauvegarde `.json`,
*Importer* la fusionne (utile pour passer du téléphone à l'ordinateur, ou pour charger l'historique Strava).
Le plan d'origine (6 semaines) est dans `index.html`, variable `SEED`. Un dépôt GitHub Pages gratuit est public :
ne mets dans le code que ce que tu acceptes de rendre visible.
