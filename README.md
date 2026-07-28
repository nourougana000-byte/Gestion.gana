# Déploiement - Gestion Gana Ousmane

Ce dépôt contient une application statique HTML/CSS/JS.

## Vérifier en local
1. Ouvrir `index.html` dans le navigateur (double-cliquer) pour tester.
2. Sur mobile, transférer le fichier et ouvrir dans le navigateur mobile ou utiliser l'inspecteur d'appareil dans Chrome/Edge.

## Déployer sur GitHub Pages
1. Créer un nouveau dépôt sur GitHub (par ex. `gestion-gana-ousmane`).
2. Initialiser git localement et pousser les fichiers:

```bash
cd "c:/Users/nouro/Downloads/2e gestion"
git init
git add .
git commit -m "Site initial"
git branch -M main
git remote add origin https://github.com/<votre-utilisateur>/<votre-repo>.git
git push -u origin main
```

3. Sur GitHub, aller dans `Settings` → `Pages` et choisir la source `main` branch `/ (root)` puis `Save`.
4. Le site sera disponible à `https://<votre-utilisateur>.github.io/<votre-repo>/` quelques minutes après.

## Conseils
- Assurez-vous que `index.html` est à la racine du repo.
- Pour modifications futures : commit + push automatiquement mettront à jour la page.

Si tu veux, je peux créer automatiquement un dépôt distant et faire le push (il faudra me donner l'URL du repo ou les identifiants si tu veux que j'exécute les commandes localement).