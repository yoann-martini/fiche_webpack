# fiche_webpack

Webpack est un module bundler c'est à dire il prend tous nos fichiers javascript, html, css ou autres et les regroupe dans un ou plusieurs modules et résout en même temps un grand probleme. Le problème est que le javascript est modulaire du coup il y'a plusieurs manières d'écrire les modules et de les importer. On a ainsi le modèle Commonjs, popularisé par nodeJs, qui se fait de maniére synchrone et le définition asynchrone de module AMD. Pour palier à ce problème, L'UMD(Universal module définition) est arrivé dans le but d'universaliser. Cependant avec la nouvelle réecriture, il y'a le ES6 module ou Harmony qui va devenir le standard dans le futur. Avec webpack on peut mélanger ces types de définitions. Wepback, associé à des loaders et des plugins, peut faire beaucoup de choses allant la mimification du code jusqu'à la mise en place d'un serveur web pour le developpement.

Pour l'installer on fait

npm install -g webpack
