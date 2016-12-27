Balise

Aussi appelée élément ou tag, c'est l'entité de base du langage HTML. Les balises sont toujours encadrées par les caractères < et >. Par exemple <html> ou encore <body>. Les balises ouvertes doivent être fermées avec une balise fermante. Par exemple </html> ou encore </body>. Certaines balises peuvent être à la fois ouvrantes et fermantes. Dans ce cas, le caractère / apparaît avant le signe > de fin de balise. Par exemple, <img src="image.jpg" />.


Attribut

Outre leur nom, certaines balises HTML peuvent recevoir une ou plusieurs informations complémentaires. Ces informations sont des attributs. Toujours spécifiés dans la balise ouvrante, ils sont suivis d'un signe = et d'une valeur entre guillemets. Lorsqu'une balise contient plusieurs attributs, ils sont séparés par des espaces. La balise <img> du code <img src="jquery.jpg" alt="logo jQuery" id="imglogo" /> contient trois attributs : src, alt et id.


Block

Les balises HTML de type block sont affichées sur des lignes successives. Par exemple, si l'on définit deux balises <div> dans un document HTML, elles seront affichées l'une en dessous de l'autre. Les balises de type block peuvent être dimensionnées, et donc occuper un espace bien défini (hauteur et largeur) dans un document.


Inline

Les balises HTML de type inline sont affichées les unes à la suite des autres. Par exemple, si l'on définit deux balises <span> dans un document HTML, elles seront affichées sur une même ligne. Les balises de type inline ne peuvent pas être dimensionnées. Elles occupent un espace qui dépend de leur contenu.


Inline-block

C'est un mélange des types inline et block. Si on définit deux balises de type inline-block dans un document HTML, elles seront affichées l'une à la suite de l'autre (c'est le comportement des balises inline). Leur taille (largeur et hauteur) pourra également être définie (c'est le comportement des balises block).


Feuille de styles

C'est un document qui rassemble un ou plusieurs styles CSS qui définissent la mise en forme d'un document. Si la feuille de styles est interne à un document, les différents styles doivent être définis dans l'en-tête du document, entre les balises <style type="text/css"> et </style>. Si la feuille de styles est externe, vous devez définir les styles dans un fichier d'extension .css et y faire référence dans l'en-tête du document en utilisant une balise <link rel="stylesheet" type="text/css" href="feuille-de-styles.css" />. Ici, la feuille de styles a pour nom feuille-de-styles.css.


Sélecteur
Type
Se rapporte à
h2
Sélecteur de balise
Toutes les balises <h2>
.rouge
Sélecteur de classe
Toutes les balises de classe rouge
#grand
Sélecteur d'identifiant
La balise d'identifiant grand
:first-letter
Sélecteur de pseudo-élément
La première lettre d'un élément
.rouge:first-letter
Sélecteur de pseudo-élément d'une classe
La première lettre des balises de classe rouge
*
Sélecteur universel
Toutes les balises
