# NexiumCodding — Site Web

Site *propre et responsive* pour présenter le **portfolio** et les **tarifs** de NexiumCodding.

## ✅ Lien direct (GitHub Pages)
Ton site sera visible ici dès que tu auras poussé les fichiers dans ce dépôt :
**https://nexiumdev.github.io/NexiumDev/**

> Si tu renomme le dépôt en `nexiumdev.github.io`, le lien deviendra :  
> **https://nexiumdev.github.io/** (plus court).

## 📂 Structure
```
/ index.html          -> le site complet
/ assets/             -> images des cartes (change-les librement)
/ data/portfolio.json -> données du portfolio (chargées au démarrage)
/ .gitignore
```

## 🛠️ Ajouter un projet au Portfolio (sans coder)
- Clique sur **« Ajouter un portfolio »** (bouton en bas à droite) sur le site.
- Remplis le formulaire (titre, description, image, tags).
- Clique **Enregistrer** : ça met à jour l’affichage *et* sauvegarde dans ton navigateur.
- Clique **Exporter JSON** : ça télécharge `portfolio.json` mis à jour.
- Uploade ce fichier dans le dossier **/data** du dépôt (remplace l’existant) pour publier.

### (Optionnel) Sauvegarde auto dans le dépôt via GitHub API
Dans la fenêtre **Admin**, renseigne :
- **Owner** : `NexiumDev`
- **Repo** : `NexiumDev`
- **Path** : `data/portfolio.json`
- **Token** : un **Personal Access Token** avec `repo` (contents:write).  
  > *Le token reste stocké en local dans ton navigateur (localStorage).*

Ensuite, clique **« Enregistrer sur GitHub »** pour publier le JSON directement.

## 🖼️ Image de fond
Place `nexium-bg.jpg` (ton fond galaxie) **à la racine** du dépôt, au même niveau que `index.html`.
Le site lira automatiquement :  
- d’abord `https://nexiumdev.github.io/NexiumDev/nexium-bg.jpg`  
- puis `./nexium-bg.jpg` en secours.

## ✏️ Personnalisation rapide
- **Logo / nom** : modifie la balise `<strong class="brand">NexiumCodding</strong>`
- **Couleurs** : cherche la variable `--primary` dans `<style>`.

---

Fait avec ❤️ pour NexiumCodding.
