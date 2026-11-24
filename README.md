# HEM-HTML-CI-Lab

TP N°1 (module DevOps, HEM) : une page web HTML avec GitHub et GitHub Actions.

## Équipe

- Achraf Aazza
- Fatima Zahra Mouhib
- Samir Labodja

## Fichiers

| Fichier | Rôle |
|---------|------|
| `index.html` | La page web |
| `style.css` | Le style de la page |
| `.github/workflows/html-ci.yml` | Le pipeline d'intégration continue |

## Intégration continue

À chaque `git push`, GitHub Actions vérifie la qualité du code HTML avec HTMLHint.
Le résultat est visible dans l'onglet **Actions** du dépôt.
