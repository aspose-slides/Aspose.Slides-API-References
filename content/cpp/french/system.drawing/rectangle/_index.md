---
title: Rectangle
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une zone rectangulaire d'une image définie par les coordonnées entières X et Y de son coin supérieur gauche ainsi que sa largeur et sa hauteur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 235
url: /fr/system.drawing/rectangle/
---
## Rectangle classe


Représente une zone rectangulaire d'une image définie par les coordonnées entières X et Y de son coin supérieur gauche ainsi que sa largeur et sa hauteur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
class Rectangle
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Construit un objet [Rectangle](./) à partir de l'objet [RectangleF](../rectanglef/) spécifié en arrondissant les valeurs de position et de taille de l'objet [RectangleF](../rectanglef/) au prochain entier supérieur. |
| **bool** [Contains](./contains/)(int, int) const | Détermine si le point spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Détermine si le point spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Détermine si le rectangle spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Détermine si les rectangles représentés par l'objet actuel et l'objet spécifié sont identiques. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Construit un nouvel objet [Rectangle](./) qui représente un rectangle avec les emplacements de bord spécifiés. |
| int [get_Bottom](./get_bottom/)() const | Renvoie la coordonnée y du bord inférieur du rectangle représenté par l'objet actuel. |
| int [get_Height](./get_height/)() const | Renvoie la hauteur du rectangle représenté par l'objet actuel. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les coordonnées X et Y du coin supérieur gauche du rectangle représenté par l'objet actuel ainsi que sa largeur et sa hauteur ont des valeurs de 0. |
| int [get_Left](./get_left/)() const | Renvoie la coordonnée X du bord gauche du rectangle représenté par l'objet actuel. |
| [Point](../point/) [get_Location](./get_location/)() const | Renvoie une instance de la classe [Point](../point/) qui spécifie la position du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| int [get_Right](./get_right/)() const | Renvoie la coordonnée X du bord droit du rectangle représenté par l'objet actuel. |
| [Size](../size/) [get_Size](./get_size/)() const | Renvoie une instance de la classe [Size](../size/) qui spécifie la largeur et la hauteur du rectangle représenté par l'objet actuel. |
| int [get_Top](./get_top/)() const | Renvoie la coordonnée Y du bord supérieur du rectangle représenté par l'objet actuel. |
| int [get_Width](./get_width/)() const | Renvoie la largeur du rectangle représenté par l'objet actuel. |
| int [get_X](./get_x/)() const | Renvoie la coordonnée X du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| int [get_Y](./get_y/)() const | Renvoie la coordonnée Y du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage de l'objet actuel. |
| void [Inflate](./inflate/)(int, int) | Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en maintenant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions des montants spécifiés. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en maintenant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions des montants spécifiés par les valeurs de largeur et hauteur de l'objet de taille spécifié de manière correspondante. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Augmente la largeur et la hauteur du rectangle représenté par l'objet spécifié, tout en maintenant la position du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions des montants spécifiés. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Remplace le rectangle représenté par l'objet actuel par le rectangle résultant de son intersection avec le rectangle représenté par l'objet spécifié. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Renvoie un rectangle qui est le résultat de l'intersection des rectangles spécifiés. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Détermine si les rectangles représentés par l'objet actuel et l'objet spécifié s'intersectent. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Décale la position du rectangle représenté par l'objet actuel des montants spécifiés. |
| void [Offset](./offset/)(int, int) | Décale la position du rectangle représenté par l'objet actuel des montants spécifiés. |
| [operator RectangleF](./operator_rectanglef/)() const | Renvoie un objet [RectangleF](../rectanglef/) qui représente un rectangle équivalent au rectangle représenté par l'objet actuel. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Renvoie toujours vrai. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Renvoie toujours faux. |
| [Rectangle](./rectangle/)() | Construit une nouvelle instance de l'objet [Rectangle](./) qui représente un rectangle avec les coordonnées X et Y ainsi que les valeurs de largeur et hauteur définies à 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Construit une nouvelle instance de l'objet [Rectangle](./) qui représente un rectangle avec les coordonnées spécifiées de son coin supérieur gauche ainsi que la largeur et la hauteur. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Construit une nouvelle instance de l'objet [Rectangle](./) qui représente un rectangle dont les coordonnées du coin supérieur gauche sont spécifiées comme une instance de la classe [Point](../point/) et sa largeur et hauteur comme une instance de la classe [Size](../size/). |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Construit une nouvelle instance de l'objet [Rectangle](./) qui représente le rectangle équivalent à celui spécifié. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Construit un objet [Rectangle](./) à partir de l'objet [RectangleF](../rectanglef/) spécifié en arrondissant les valeurs de position et de taille de l'objet [RectangleF](../rectanglef/) aux entiers les plus proches. |
| void [set_Height](./set_height/)(int) | Définit la hauteur du rectangle représenté par l'objet actuel. |
| void [set_Location](./set_location/)([Point](../point/)) | Définit la position du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| void [set_Size](./set_size/)([Size](../size/)) | Définit la largeur et la hauteur du rectangle représenté par l'objet actuel. |
| void [set_Width](./set_width/)(int) | Définit la largeur du rectangle représenté par l'objet actuel. |
| void [set_X](./set_x/)(int) | Définit la coordonnée X du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| void [set_Y](./set_y/)(int) | Définit la coordonnée Y du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| [String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de l'objet actuel. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Construit un objet [Rectangle](./) à partir de l'objet [RectangleF](../rectanglef/) spécifié en tronquant les valeurs de position et de taille de l'objet [RectangleF](../rectanglef/) au prochain entier inférieur. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Renvoie un rectangle qui est le résultat de l'union des rectangles spécifiés. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Un rectangle vide, c’est-à-dire un rectangle dont les valeurs de position et de taille sont nulles. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)