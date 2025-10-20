# TP  Blaise kokou MOUVI

Partie 1

1- Qu’est-ce que JavaScript et son role dans le developemnt web
JavaScript est un langage de programmation utilisé pour rendre les pages web interactives.  
Il permet d’ajouter des animations, de valider des formulaires, de modifier dynamiquement le contenu et d’améliorer l’expérience utilisateur.

2- Comment utilisez-vous les media queries en CSS ?

Les media queries servent à adapter le design d’un site selon la taille de l’écran (ordinateur, tablette, mobile).

```css
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}

3-
On peut utiliser la propriété display: grid pour créer une grille flexible.

.container {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 20px;
}

4-
Les pseudo-classes permettent d’appliquer des styles selon l’état d’un élément
button:hover {
  background-color: blue;
  color: white;
}

5-
HTML (HyperText Markup Language) est le langage de base du web.
Il sert à structurer le contenu d’une page (titres, textes, images, lien, video,).

6-
<html>
  <head>
    <title>Titre de la page</title>
  </head>
  <body>
    <h1>Titre principal</h1>
    <p>Texte du paragraphe</p>
  </body>
</html>

<html> : structure de base

<head> : informations du document

<body> : contenu visible de la page
<>


7- Pour inserer une image dans une page html j'applique ce code voici
<img src="image.jpg" alt="Description de l'image">

8- pour creer un lien hypertexte dans une page html j'applique ce code <a href="https://example.com">Visitez le site</a>

9- Le modele de boite CSS est que  Chaque élément HTML est une boîte composée de :
content + padding + border + margin. Elle s"applique comme ceci 
div {
  width: 200px;
  padding: 10px;
  border: 2px solid black;
  margin: 20px;
}

10-La  valeur non valide pour display
Réponse : d) vertical

11- Pour centrer un element en utilisant css jutilise margin et width
div { margin: 0 auto; width: 50%; }

12-  Le responsive design permet à un site de s’adapter à tous les écrans (mobile, tablette, PC).

13-
13. Différence inline vs block

block : occupe toute la largeur (<div>, <p>) tandis que 

inline : occupe juste la largeur du contenu (<span>,<a> )

14- 
la propriété float permet de placer les éléments côte à côte.
img {
  float: left;
  margin-right: 10px;
}

15-
le modele de boite et composant

Composants du modèle de boîte CSS

Content> le contenu (texte, image, etc.)

Padding >  espace intérieur entre le contenu et la bordure

Border> la bordure de l’élément

Margin> espace extérieur autour de l’élément




