# Demo VV - Projet Panorama VR

Ce projet contient un panorama virtuel interactif créé avec Pano2VR.

## Contenu du projet

- **Panoramas VR** : Visite virtuelle avec plusieurs nœuds (node19 à node24)
- **Interface utilisateur** : Skin personnalisé pour la navigation
- **Plans d'étage** : Cartes de navigation avec FloorPlan_1 et FloorPlan_2
- **Support WebXR** : Compatible avec les casques de réalité virtuelle

## Structure des fichiers

- `pano.xml` : Fichier de configuration principal du panorama
- `pano2vr_player.js` : Lecteur Pano2VR
- `skin.js` / `skin_vr.js` : Interface utilisateur pour web et VR
- `tiles/` : Tuiles d'images pour chaque nœud panoramique
- `images/` : Images de navigation et cartes
- `images_vr/` : Miniatures des nœuds pour la navigation
- `webxr/` : Ressources spécifiques pour WebXR

## Utilisation

1. Ouvrez le fichier principal dans un navigateur web
2. Naviguez entre les différents points de vue en cliquant sur les hotspots
3. Utilisez les contrôles de navigation pour explorer le panorama
4. Pour l'expérience VR, utilisez un casque compatible WebXR

## Technologies utilisées

- Pano2VR (Garden Gnome Software)
- JavaScript
- WebXR pour la réalité virtuelle
- Format d'images en tuiles pour un chargement optimisé

---
Créé avec Pano2VR