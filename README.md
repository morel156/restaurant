# SIKIRA'S FOOD

Page vitrine pour **SIKIRA'S FOOD**, un restaurant béninois (spécialités traditionnelles africaines) fondé le 1er janvier 2025 à Bohicon par sa directrice générale, Osseni Sikiratou.

## Contenu de la page

La page d'accueil (`index.html`) présente :

- **En-tête** : logo/nom du restaurant, un menu de navigation (Accueil, Menu, Contact, Paiement) et une accroche (« Le plaisir Aujourd'hui Demain Toujours »).
- **Biographie** : présentation du restaurant, de son histoire et de sa fondatrice.
- **« Notre carnevat »** : les trois moments de la journée où le restaurant sert ses plats — matin (petit-déjeuner), après-midi (déjeuner + dessert) et soir (dîner + dessert).
- **Pied de page** : slogan du restaurant et liens vers ses réseaux sociaux (Twitter, Telegram, Instagram, LinkedIn).

Les liens de navigation vers `accueil.html`, `menu.html`, `contact.html` et `payement.html` renvoient vers des pages qui ne sont pas (encore) présentes dans ce dépôt ; seule `index.html` existe actuellement.

## Stack technique

- **HTML5** pour la structure (`index.html`)
- **CSS3** pour la mise en forme (`style.css`), sans framework ni préprocesseur
- Aucun JavaScript, aucune dépendance externe

## Voir le site en local

Aucune installation n'est nécessaire :

1. Cloner ou télécharger ce dépôt.
2. Ouvrir le fichier `index.html` directement dans un navigateur.

Ou, pour un rendu plus proche d'un vrai serveur (recommandé pour éviter d'éventuels soucis de chemins relatifs) :

```bash
# avec Python
python -m http.server 8000

# avec l'extension VS Code "Live Server"
```

Puis ouvrir `http://localhost:8000` dans un navigateur.
