---
title: RectangleF
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une zone rectangulaire d'une image définie par des coordonnées X et Y à précision simple en virgule flottante de son coin supérieur gauche ainsi que sa largeur et sa hauteur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 248
url: /fr/system.drawing/rectanglef/
---
## RectangleF classe

Représente une zone rectangulaire d'une image définie par des coordonnées X et Y à précision simple en virgule flottante de son coin supérieur gauche ainsi que sa largeur et sa hauteur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
class RectangleF
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Détermine si le point spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Détermine si le point spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Détermine si le rectangle spécifié est situé à l'intérieur du rectangle représenté par l'objet actuel. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Détermine si les rectangles représentés par l'objet actuel et l'objet spécifié sont identiques. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Construit un nouvel objet [RectangleF](./) qui représente un rectangle avec les emplacements de bord spécifiés. |
| **float** [get_Bottom](./get_bottom/)() const | Renvoie la coordonnée y du bord inférieur du rectangle représenté par l'objet actuel. |
| **float** [get_Height](./get_height/)() const | Renvoie la hauteur du rectangle représenté par l'objet actuel. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les coordonnées X et Y du coin supérieur gauche du rectangle représenté par l'objet actuel ainsi que sa largeur et sa hauteur ont des valeurs de 0. |
| **float** [get_Left](./get_left/)() const | Renvoie la coordonnée X du bord gauche du rectangle représenté par l'objet actuel. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Renvoie une instance de la classe [PointF](../pointf/) qui spécifie l'emplacement du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| **float** [get_Right](./get_right/)() const | Renvoie la coordonnée X du bord droit du rectangle représenté par l'objet actuel. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Renvoie une instance de la classe [SizeF](../sizef/) qui spécifie la largeur et la hauteur du rectangle représenté par l'objet actuel. |
| **float** [get_Top](./get_top/)() const | Renvoie la coordonnée Y du bord supérieur du rectangle représenté par l'objet actuel. |
| **float** [get_Width](./get_width/)() const | Renvoie la largeur du rectangle représenté par l'objet actuel. |
| **float** [get_X](./get_x/)() const | Renvoie la coordonnée X du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| **float** [get_Y](./get_y/)() const | Renvoie la coordonnée Y du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage de l'objet actuel. |
| void [Inflate](./inflate/)(**float**, **float**) | Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant l'emplacement du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les valeurs spécifiées. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Augmente la largeur et la hauteur du rectangle représenté par l'objet actuel, tout en conservant l'emplacement du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les valeurs de largeur et de hauteur de l'objet size spécifié correspondamment. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Augmente la largeur et la hauteur du rectangle représenté par l'objet spécifié, tout en conservant l'emplacement du centre géométrique du rectangle. La largeur et la hauteur sont augmentées dans les deux directions par les valeurs spécifiées. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Remplace le rectangle représenté par l'objet actuel par le rectangle résultant de son intersection avec le rectangle représenté par l'objet spécifié. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Renvoie un rectangle qui est le résultat de l'intersection des rectangles spécifiés. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Détermine si les rectangles représentés par les objets actuel et spécifié intersectent. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Décale la position du rectangle représenté par l'objet actuel des montants spécifiés. |
| void [Offset](./offset/)(**float**, **float**) | Décale la position du rectangle représenté par l'objet actuel des montants spécifiés. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Renvoie toujours vrai. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Renvoie toujours faux. |
| [RectangleF](./rectanglef/)() | Construit une nouvelle instance de l'objet [RectangleF](./) qui représente un rectangle avec les coordonnées X et Y ainsi que les valeurs de largeur et hauteur égales à 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Construit une nouvelle instance de l'objet [RectangleF](./) qui représente un rectangle avec les coordonnées spécifiées de son coin supérieur gauche ainsi que sa largeur et sa hauteur. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Construit une nouvelle instance de l'objet [RectangleF](./) qui représente un rectangle dont les coordonnées du coin supérieur gauche sont spécifiées comme une instance de la classe [PointF](../pointf/) et sa largeur et hauteur comme une instance de la classe [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Construit une nouvelle instance de l'objet [RectangleF](./) qui représente le rectangle équivalent à celui spécifié. |
| void [set_Height](./set_height/)(**float**) | Définit la hauteur du rectangle représenté par l'objet actuel. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Définit l'emplacement du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Définit la largeur et la hauteur du rectangle représenté par l'objet actuel. |
| void [set_Width](./set_width/)(**float**) | Définit la largeur du rectangle représenté par l'objet actuel. |
| void [set_X](./set_x/)(**float**) | Définit la coordonnée X du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| void [set_Y](./set_y/)(**float**) | Définit la coordonnée Y du coin supérieur gauche du rectangle représenté par l'objet actuel. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de l'objet actuel. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Renvoie un rectangle qui est le résultat de l'union des rectangles spécifiés. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Un rectangle vide, c’est-à-dire un rectangle dont les valeurs de localisation et de taille sont nulles. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)