---
title: Point
second_title: Référence API Aspose.Slides pour C++
description: "Représente une paire de coordonnées entières X et Y d'un point sur un plan à deux dimensions. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. Ne jamais utiliser la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 209
url: /fr/system.drawing/point/
---
## Point classe

Représente une paire de coordonnées entières X et Y d'un point sur un plan à deux dimensions. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. Ne jamais utiliser la classe [System::SmartPtr](../../system/smartptr/) pour gérer des objets de ce type.

```cpp
class Point
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Ajoute les valeurs de largeur et de hauteur de l'objet [Size](../size/) spécifié aux valeurs des coordonnées X et Y de l'objet [Point](./) spécifié respectivement. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Construit un objet [Point](./) à partir de l'objet [PointF](../pointf/) spécifié en arrondissant les valeurs des coordonnées X et Y de l'objet [PointF](../pointf/) au prochain entier supérieur. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Détermine si l'objet actuel et l'objet spécifié sont égaux, c'est-à-dire représentent la même paire de valeurs de coordonnées X et Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les valeurs des coordonnées X et Y sont toutes deux égales à 0. |
| int [get_X](./get_x/)() const | Renvoie la valeur de la coordonnée X représentée par l'objet actuel. |
| int [get_Y](./get_y/)() const | Renvoie la valeur de la coordonnée Y représentée par l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
| size_t [getStdHash](./getstdhash/)() const | Renvoie une valeur de hachage pour l'objet actuel. |
| **bool** [IsNull](./isnull/)() const | Renvoie toujours false. |
| void [Offset](./offset/)(int, int) | Décale les valeurs des coordonnées X et Y représentées par l'objet actuel des valeurs spécifiées. |
| void [Offset](./offset/)([Point](./)) | Décale les coordonnées X et Y représentées par l'objet actuel des valeurs des coordonnées X et Y représentées par l'objet [Point](./) spécifié respectivement. |
|  [operator PointF](./operator_pointf/)() const | Construit une instance de l'objet [PointF](../pointf/) et l'initialise avec les valeurs des coordonnées X et Y de l'objet [Point](./) actuel. |
|  [operator Size](./operator_size/)() const | Construit une instance de l'objet [Size](../size/) et initialise ses valeurs de largeur et de hauteur avec les valeurs des coordonnées X et Y représentées par l'objet actuel respectivement. |
|  [Point](./point/)() | Construit un nouvel objet [Point](./) et initialise ses valeurs de coordonnées X et Y à 0. |
|  [Point](./point/)(int, int) | Construit un nouvel objet [Point](./) et l'initialise avec les valeurs spécifiées. |
|  [Point](./point/)(const [Size](../size/)\&) | Construit un nouvel objet [Point](./) et initialise ses valeurs de coordonnées X et Y avec les valeurs de largeur et de hauteur de l'objet [SizeF](../sizef/) spécifié respectivement. |
|  [Point](./point/)(int) | Construit un nouvel objet [Point](./) et initialise la valeur de sa coordonnée X avec une valeur formée par les 16 bits supérieurs de l'entier 32 bits spécifié et la valeur de sa coordonnée Y avec une valeur formée par les 16 bits inférieurs de l'entier 32 bits spécifié. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Construit un objet [Point](./) à partir de l'objet [PointF](../pointf/) spécifié en arrondissant les valeurs des coordonnées X et Y de l'objet [PointF](../pointf/) à la valeur entière la plus proche. |
| void [set_X](./set_x/)(int) | Définit la valeur de la coordonnée X représentée par l'objet actuel. |
| void [set_Y](./set_y/)(int) | Définit la valeur de la coordonnée Y représentée par l'objet actuel. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Soustrait les valeurs de largeur et de hauteur de l'objet [Size](../size/) spécifié des valeurs des coordonnées X et Y de l'objet [Point](./) spécifié respectivement. |
| [String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de la paire de valeurs de coordonnées X et Y représentée par l'objet actuel. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Construit un objet [Point](./) à partir de l'objet [PointF](../pointf/) spécifié en tronquant les valeurs des coordonnées X et Y de l'objet [PointF](../pointf/) au prochain entier inférieur. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Une instance vide de la classe [Point](./) dont les valeurs des coordonnées X et Y sont 0. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)