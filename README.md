# Les Coffrets Gourmands

Site vitrine en HTML et CSS pour **Les Coffrets Gourmands**, l'activité de vente en ligne de coffrets gourmands de Charlotte Bon Goût, auto-entrepreneure (cas pratique fictif).

Projet réalisé en **BTS SIO 1re année**, bloc 1 « Support et mise à disposition des services informatiques », mission 2 : développer la présence en ligne de l'organisation cliente.

![Page d'accueil](docs/captures/index-ordinateur.jpg)

## Le site

| Page | Fichier | Contenu |
|---|---|---|
| Accueil | `index.html` | Présentation de Charlotte, contenu d'un coffret sur étiquette, ardoise des 5 coffrets avec leurs prix, infos pratiques, ambiance sonore du marché |
| Nos coffrets | `coffrets.html` | Contenu détaillé des 5 coffrets (produits, poids, producteur), vidéo de préparation d'une commande, tableau récapitulatif, bon de commande |
| Producteurs partenaires | `producteurs.html` | Tableau des 6 producteurs : nom, catégorie, horaires, produit signature et coffrets concernés |

Les trois pages partagent le même menu et la même feuille de style (`style.css`). Le site s'adapte aux écrans d'ordinateur, de tablette et de téléphone.

### Balises HTML utilisées

Titres (`h1`, `h2`), paragraphes, liens entre les pages et vers des ancres (`coffrets.html#gouter`), images avec texte alternatif, son (`audio`), vidéo (`video`), boutons, tableaux (`table`, `caption`, `thead`, `tbody`), listes, liste de définitions (`dl`) et formulaire (`form`, `label`, `input`, `select`, `textarea`).

## Ouvrir le projet

Aucune installation n'est nécessaire.

1. Télécharger le dépôt (bouton **Code**, puis **Download ZIP**) et l'extraire, ou le cloner :
   ```
   git clone https://github.com/svjAbdel/Coffret-gourmand.git
   ```
2. Ouvrir le dossier dans Visual Studio Code (**Fichier**, puis **Ouvrir le dossier…**).
3. Ouvrir `index.html` dans un navigateur, ou utiliser l'extension **Live Server** de VS Code (clic droit sur `index.html`, puis **Open with Live Server**).

Garder les fichiers HTML, `style.css` et les dossiers `images/`, `audio/`, `videos/` et `polices/` ensemble : les pages y font référence par des chemins relatifs.

## Structure du dépôt

```
.
├── index.html            Accueil
├── coffrets.html         Nos coffrets
├── producteurs.html      Producteurs partenaires
├── style.css             Feuille de style commune
├── images/               Photos des coffrets, de Charlotte et du verger
├── audio/                Ambiance sonore du marché
├── videos/               Vidéo de préparation d'une commande
├── polices/              Polices hébergées localement (licence OFL)
└── docs/captures/        Captures d'écran du site (ordinateur et téléphone)
```

## Choix graphiques

L'univers visuel reprend les objets du métier de Charlotte plutôt qu'un modèle de site générique :

- **Couleurs** : le kraft des boîtes (fond), un brun confiture pour le texte, le rouge cire à cacheter réservé aux prix et aux boutons, un vert laurier pour les mentions bio, et une ardoise sombre pour la liste des prix.
- **Typographie** : *Big Shoulders Display*, une police condensée proche du lettrage au pochoir des caisses de marché, pour les titres ; *Literata*, une police de lecture, pour les textes.
- **Mise en page** : une étiquette kraft qui détaille le contenu d'un coffret, une ardoise de prix comme sur un étal, une liste des coffrets présentée comme un bon de colisage et un formulaire en forme de bon de commande.

## Aperçu sur téléphone

<p>
  <img src="docs/captures/index-telephone.jpg" alt="Accueil sur téléphone" width="240">
  <img src="docs/captures/coffrets-telephone.jpg" alt="Nos coffrets sur téléphone" width="240">
  <img src="docs/captures/producteurs-telephone.jpg" alt="Producteurs sur téléphone" width="240">
</p>

## Crédits et licences

- **Polices** : Big Shoulders Display et Literata, sous licence SIL Open Font License 1.1 (textes de licence dans `polices/`).
- **Vidéo** : Pexels, vidéo n° 7855140 (licence Pexels), réduite en 720p.
- **Son** : ambiance de marché, Pixabay (licence Pixabay).
- **Photos** : *source à compléter*.

Le code HTML et CSS est publié sous licence [MIT](LICENSE). Les médias restent soumis à leurs licences d'origine.

## Contenu fictif

Charlotte Bon Goût, les producteurs, les prix, les délais et les tarifs de livraison sont inventés pour l'exercice. Le bon de commande n'envoie aucune donnée.

## Auteur

[svjAbdel](https://github.com/svjAbdel), BTS SIO 1re année.
