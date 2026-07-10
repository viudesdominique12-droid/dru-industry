# DRU INDUSTRY — Company Web Profile

Profil web (site vitrine haut de gamme) de **DRU INDUSTRY / French Pastry** — conception, développement et mise en œuvre de projets agroalimentaires en Afrique.

Site statique autonome : un seul `index.html` (polices, images et carte de l'Afrique intégrées en base64), accompagné des vidéos.

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Le site complet — navigation type application, 9 pages (Accueil, À propos, Activités, Expertise, Notre approche, Projets, Contact, Mentions légales, Confidentialité) |
| `video-1.mp4` | Vidéo de la section citation (Accueil) |
| `video-2.mp4`, `video-3.mp4` | Vidéos de la page Expertise |

## Caractéristiques

- Design premium (bleu nuit / blanc / gris + doré), responsive mobile et ordinateur.
- Conforme **RGPD / CNIL / LCEN** : aucune ressource tierce chargée automatiquement, mentions légales et politique de confidentialité intégrées.
- Formulaire de contact envoyant directement (via FormSubmit).
- Lecteurs vidéo cliquables, sans plein écran, avec pause automatique au défilement.

## Déploiement

Hébergement statique : servir `index.html` à la racine, les fichiers `video-*.mp4` dans le même dossier. Déployé via **Vercel**.
