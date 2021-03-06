# Étape 2 - Travail à réaliser

Bonjour ! Voici le site que j'ai réalisé pour la 4ème étape des travaux à réaliser. C'est le travail qui a monopolisé la majorité de mon temps.

## Apprentissage du CSS et de l'HTML

Lorsque j'ai reçu le mail indiquant les exercices à rendre, j'ai décidé de me concentrer sur le quatrième. En effet, il était dans la lignée de ce que j'étais en train d'étudier puisque j’'avais commencé à apprendre le webdesign sur [ce site](http://www.steaw-webdesign.com/css/). J'ai donc parcouru ce tutoriel plusieurs fois et me suis attelé à la réalisation du site lartystyle, commandé par une amie.  Elle travaille en tant que chargée de communication digitale à Coca-Cola France et voulait développer un site internet mêlant art, mode et lifestyle. J’ai donc voulu prendre par à cette aventure qui me semble intéressante et qui lui tient à coeur. 

## Le site

Mon principal objectif dans le développement du site est qu'il soit totalement responsif. Pour ce faire j'ai lu l'article de John Allsop, [A Dao of Web Design](http://alistapart.com/article/dao), et le livre de Ethan Marcotte, [Responsive Web Design](http://abookapart.com/products/responsive-web-design).

J'ai étudié ce livre tout en créant le site, il m'a permis de m'exercer et de comprendre les concepts évoqués. Une fois le dossier envoyé je pense que je reprendrais le site à zéro pour établir une grille responsive et avoir un code beaucoup plus 'light' (il y a sûrement beaucoup de code inutile. J'ai utilisé beaucoup de feuilles de style pour m'y retrouver plus facilement, mais c'est sûrement très mauvais au niveau performance et ça complique la tâche pour trouver les bouts de codes redondants).

Le site ne présente qu'une page et le form newsletter ne marche pas encore. Je n'ai pas encore eu le temps d'étudier le javascript et je ne voulais pas qu'il y ai de code copié collé sur le site (à part le script Typekit !).

## Les problèmes du site

<strike>Outre l'absence de contenu, l'absence de menu en haut de la page est peut-être un problème. J'ai fait le choix de placer la navigation dans la footer, pour que l'utilisateur y ai accès une fois avoir visionné le contenu, mais ça peut causer de la confusion chez certains utilisateurs.</strike> *J'ai rajouté un menu car les retours que j'ai eu déploraient son absence.*

Je ne me suis pas encore penché sur les "vendor prefixes" et mon site n'est surement pas optimisé pour certains navigateurs (notamment pour la propriété *transition*).

Les images ne sont pas responsives ! Je n'ai pas encore eu le temps de créer des images particulères pour certains appareils. Le site n'est en fait absolument pas optimisé niveau performance. C'est quelque chose dont j'ai pris conscience en cours de réalisation, qui sera dans mon esprit à chaque instant dans l'élaboration de la nouvelle version. Il faut aussi créer une image de header spécifique pour les smartphones (puisqu'elle est affichée avec 100vh sur ces appareils, donc dans un format portrait).

Je ne trouve pas la footer très esthétique. Je ne sais pas du tout comment la styliser.

Les titres des éléments (*h2*) sont déséquilibrés, tout comme certains paragraphes à certaines tailles d'écrans. J'ai essayé d'utiliser `text-align: justify` mais ça créait des lignes très bizarres parfois.

De plus, il faudrait un élément qui informe l'utilisateur du but du site s'il arrive dessus par hasard. C'est la fonction du sous-titre "1 STYLE = 4 REFERENCES ARTY", mais il n'est probablement pas assez explicite.

Il faut aussi que je crée un logo pour utiliser en .ico du site.

Le css est assez mal organisé. Pour mon prochain projet j'utiliserai probablement [ces guidelines](http://mdo.github.io/code-guide/) parce qu'actuellement il est trop dur de trouver un élément particulier dans le css sans utiliser ctrl+f, et une collaboration sur un tel code serait particulièrement malaisée.

### Notes

Le code n'est pas indenté correctement parce que je me suis forcé à coder dans le bloc note de windows pour tout écrire sans avoir de raccourcis et bien apprendre la syntax.