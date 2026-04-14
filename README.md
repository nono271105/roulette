# Roulette des Sujets (Topic Roulette)

Une application web simple et dynamique pour tirer au sort un sujet de discussion et lancer un chronomètre. Idéal pour s'entraîner à parler en public, lancer des débats ou tout simplement s'amuser.

## Fonctionnalités

* **Tirage Aléatoire & Fluide** : Une roue animée qui tire au sort un sujet parmi une liste définie.
* **Système Bilingue (FR / EN)** : Basculez entre le français et l'anglais d'un simple clic. La préférence est sauvegardée.
* **Personnalisable** :
  * Saisissez vos propres thèmes de discussion.
  * Changez la durée du chronomètre (30s, 60s, 5m, etc.).
* **Anti-répétition** : Le système empêche de tomber deux fois de suite sur le même sujet.
* **Minuteur intégré** : Avec des couleurs qui changent lorsque le temps presse, et une pluie de confettis à la fin !
* **Accessibilité (A11y)** : Fonctionne entièrement avec le clavier et intègre des annonces pour les lecteurs d'écran.
* **Sauvegarde Locale** : Les données (langue, sujets personnalisés, durée du chrono) sont enregistrées dans votre navigateur.

## Comment lancer l'application ?

Le projet est construit entièrement en **Vanilla HTML / CSS / JS** et ne nécessite aucune installation de dépendances.

Pour l'utiliser :

1. Téléchargez ou cloner ce repository.
2. Double-cliquez sur le fichier `roulette.html` pour l'ouvrir dans votre navigateur web préféré (Chrome, Safari, Firefox).
3. (Optionnel) Vous pouvez aussi utiliser une extension comme *Live Server* sur VS Code pour lancer un serveur de développement.

## Structure du projet

* `roulette.html` : L'interface principale, contenant la structure HTML, la stylisation CSS et la logique du chronomètre et de la roue (JavaScript).
* `topics.js` : Un fichier de données externe qui contient les listes des sujets par défaut en français et en anglais.

## Technologies utilisées

* HTML5 (Sémantique & ARIA)
* CSS3 (Variables CSS, Animations, Media Queries)
* JavaScript (ES6, Vanilla JS, LocalStorage)
