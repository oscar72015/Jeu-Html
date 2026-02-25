# 🎮 Chouteur – Version HTML / Canvas

Un remake complet du jeu Pygame **entièrement recodé en HTML + JavaScript**, jouable directement dans le navigateur.  
Le jeu utilise un `<canvas>` pour afficher :

- le joueur  
- les monstres  
- les projectiles  
- les comètes  
- la barre d’événement  
- l’écran d’accueil avec bouton PLAY  

---

## 🖼️ Aperçu du jeu

### Écran d’accueil
![Accueil](Jeu/PygameAssets-main/banner.png)

### Gameplay
![Gameplay](Jeu/PygameAssets-main/bg.jpg)

### Joueur
![Player](Jeu/PygameAssets-main/player.png)

### Ennemi
![Monster](Jeu/PygameAssets-main/mummy.png)

### Projectile
![Projectile](Jeu/PygameAssets-main/projectile.png)

### Comète
![Comet](Jeu/PygameAssets-main/comet.png)

---

## 📁 Structure du projet

Jeu-Html/
│
├── main.html
│
└── PygameAssets-main/
├── bg.jpg
├── banner.png
├── button.png
├── player.png
├── mummy.png
├── projectile.png
└── comet.png

Code

---

## 🚀 Lancer le jeu

### ✔️ Méthode simple  
Ouvre simplement **main.html** dans ton navigateur.

### ✔️ Méthode recommandée (serveur local)  
Certaines versions de Chrome/Edge bloquent les images locales.  
Dans ce cas, lance un petit serveur :

```bash
python -m http.server
