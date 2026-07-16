---
title: SizeF
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une paire de valeurs à virgule flottante simple précision qui représente la largeur et la hauteur d'une image. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 287
url: /fr/system.drawing/sizef/
---
## SizeF classe


Représente une paire de valeurs à virgule flottante simple précision qui représente la largeur et la hauteur d'une image. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
class SizeF
```

## Méthodes

| Method | Description |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Renvoie un nouvel objet [SizeF](./) qui est la somme des objets [SizeF](./) spécifiés, c’est-à-dire dont la valeur de largeur est égale à la somme des valeurs de largeur des objets spécifiés et dont la valeur de hauteur est égale à la somme des valeurs de hauteur des objets spécifiés. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Détermine si l'objet actuel et l'objet spécifié sont égaux, c’est-à-dire représentent la même paire de valeurs de largeur et de hauteur. |
| **float** [get_Height](./get_height/)() const | Renvoie la valeur de hauteur représentée par l'objet actuel. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les valeurs de largeur et de hauteur sont toutes deux égales à 0. |
| **float** [get_Width](./get_width/)() const | Renvoie la valeur de largeur représentée par l'objet actuel. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
| [operator PointF](./operator_pointf/)() const | Convertit l'objet actuel en une instance de l'objet [Point](../point/) en initialisant ses coordonnées X et Y avec les valeurs de largeur et de hauteur de l'objet actuel respectivement. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Ajoute les valeurs de largeur et de hauteur de l'objet [SizeF](./) spécifié aux valeurs de largeur et de hauteur de l'objet [SizeF](./) actuel respectivement. |
| void [set_Height](./set_height/)(**float**) | Définit la valeur de hauteur représentée par l'objet actuel. |
| void [set_Width](./set_width/)(**float**) | Définit la valeur de largeur représentée par l'objet actuel. |
| [SizeF](./sizef/)() | Construit un nouvel objet [SizeF](./) et initialise ses valeurs de largeur et de hauteur à 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Construit un nouvel objet [SizeF](./) et initialise ses valeurs de largeur et de hauteur avec les valeurs des coordonnées X et Y du point spécifié respectivement. |
| [SizeF](./sizef/)(**float**, **float**) | Construit un nouvel objet [SizeF](./) et l'initialise avec la valeur spécifiée. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Renvoie un nouvel objet [SizeF](./) qui est le résultat de la soustraction de **size2** à partir de **size1**, c’est-à-dire dont la valeur de largeur est le résultat de la soustraction de la valeur de largeur de **size2** à celle de **size1** et dont la valeur de hauteur est le résultat de la soustraction de la valeur de hauteur de **size2** à celle de **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Convertit l'objet actuel en une instance de l'objet [Point](../point/) en initialisant ses coordonnées X et Y avec les valeurs de largeur et de hauteur de l'objet actuel respectivement. |
| [Size](../size/) [ToSize](./tosize/)() const | Construit un objet [Size](../size/) à partir de l'objet [SizeF](./) actuel en tronquant les valeurs de largeur et de hauteur de l'objet [SizeF](./) aux entiers inférieurs suivants. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de la paire de valeurs de largeur et de hauteur représentée par l'objet actuel. |

## Champs

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Une instance vide de la classe [SizeF](./) dont les valeurs de largeur et de hauteur sont 0. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)