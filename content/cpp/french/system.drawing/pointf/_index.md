---
title: PointF
second_title: Référence API Aspose.Slides pour C++
description: "Représente une paire de coordonnées X et Y en virgule flottante simple précision d'un point sur un plan bidimensionnel. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 222
url: /fr/system.drawing/pointf/
---
## PointF classe

Représente une paire de coordonnées X et Y à virgule flottante simple précision d’un point sur un plan à deux dimensions. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N’utilisez jamais la [System::SmartPtr](../../system/smartptr/) classe pour gérer les objets de ce type.

```cpp
class PointF
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Ajoute les valeurs de largeur et de hauteur de l’objet [SizeF](../sizef/) spécifié aux valeurs des coordonnées X et Y de l’objet [PointF](./) spécifié, respectivement. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Ajoute les valeurs de largeur et de hauteur de l’objet [Size](../size/) spécifié aux valeurs des coordonnées X et Y de l’objet [PointF](./) spécifié, respectivement. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Détermine si l’objet actuel et l’objet spécifié sont égaux, c’est-à-dire représentent la même paire de valeurs de coordonnées X et Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les valeurs des coordonnées X et Y sont toutes deux égales à 0. |
| **float** [get_X](./get_x/)() const | Renvoie la valeur de la coordonnée X représentée par l’objet actuel. |
| **float** [get_Y](./get_y/)() const | Renvoie la valeur de la coordonnée Y représentée par l’objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l’objet actuel. |
| **bool** [IsNull](./isnull/)() const | Renvoie toujours false. |
| explicit  [operator bool](./operator_bool/)() | Renvoie toujours true. |
|  [PointF](./pointf/)() | Construit un nouvel objet [PointF](./) et initialise ses valeurs de coordonnées X et Y à 0. |
|  [PointF](./pointf/)(**float**, **float**) | Construit un nouvel objet [PointF](./) et l’initialise avec les valeurs spécifiées. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Construit un nouvel objet [PointF](./) et initialise ses valeurs de coordonnées X et Y avec les valeurs de largeur et de hauteur de l’objet [SizeF](../sizef/) spécifié, respectivement. |
| void [set_X](./set_x/)(**float**) | Définit la valeur de la coordonnée X représentée par l’objet actuel. |
| void [set_Y](./set_y/)(**float**) | Définit la valeur de la coordonnée Y représentée par l’objet actuel. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Soustrait les valeurs de largeur et de hauteur de l’objet [SizeF](../sizef/) spécifié des valeurs des coordonnées X et Y de l’objet [PointF](./) spécifié, respectivement. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Soustrait les valeurs de largeur et de hauteur de l’objet [Size](../size/) spécifié des valeurs des coordonnées X et Y de l’objet [PointF](./) spécifié, respectivement. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de la paire de valeurs de coordonnées X et Y représentée par l’objet actuel. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Une instance vide de la classe [PointF](./) dont les valeurs des coordonnées X et Y sont 0. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)