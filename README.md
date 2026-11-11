# TRIVIA — Jeu de culture générale

TRIVIA est un jeu de quiz responsive en français. Il fonctionne directement dans un navigateur, sans installation et sans serveur.

## Lancer le jeu

1. Télécharge et décompresse `TRIVIA.zip`.
2. Ouvre le dossier `TRIVIA`.
3. Double-clique sur `index.html`.
4. Le jeu s'ouvre dans ton navigateur : tu peux jouer.

Tu peux aussi ouvrir `index.html` directement depuis Visual Studio Code avec l'aperçu ou l'extension Live Server.

## Fichiers

- `index.html` : structure des écrans et contenu HTML.
- `styles.css` : design, animations et adaptation aux petits écrans.
- `app.js` : questions, chronomètre, réponses, calcul des points et sauvegarde des records.

## Contenu du jeu

- 96 questions originales de culture générale.
- 8 catégories : Culture, Sciences, Histoire, Géographie, Sport, Arts, Technologie et Mathématiques.
- 3 niveaux de difficulté : facile, moyen et difficile, avec sélection mixte.
- Parties de 8, 12 ou 20 questions (la partie est limitée si une sélection contient moins de questions).
- 20 secondes par question.
- Points, bonus de rapidité et bonus de série.
- Classement local des meilleurs scores.
- Mise en page responsive pour ordinateur, tablette et téléphone.

## Sauvegarde des scores

Les records sont stockés dans le `localStorage` du navigateur, sur l'appareil utilisé. Ils ne sont ni envoyés sur un serveur ni partagés avec d'autres joueurs. Le classement est donc local, pas un classement mondial en ligne.

## Notes

Le jeu ne nécessite aucune bibliothèque JavaScript. Une connexion Internet n'est pas nécessaire pour jouer ; la police personnalisée peut simplement ne pas se charger hors ligne, auquel cas une police de remplacement est utilisée.
