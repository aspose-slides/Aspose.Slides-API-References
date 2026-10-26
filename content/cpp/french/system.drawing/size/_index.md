---
title: Size
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une paire de valeurs entières qui représentent la largeur et la hauteur d'une image. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 274
url: /fr/system.drawing/size/
---
## Classe de taille

Représente une paire de valeurs entières qui représentent la largeur et la hauteur d'une image. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N’utilisez jamais [System::SmartPtr](../../system/smartptr/) classe pour gérer les objets de ce type.

```cpp
class Size
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Renvoie un nouvel objet [Size](./) qui est la somme de l'objet [Size](./) spécifié, c’est-à-dire dont la valeur de largeur est égale à la somme des valeurs de largeur des objets spécifiés et la valeur de hauteur est égale à la somme des valeurs de hauteur des objets spécifiés. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Construit un objet [Size](./) à partir de l'objet [SizeF](../sizef/) spécifié en arrondissant les valeurs de largeur et de hauteur de l'objet [SizeF](../sizef/) à l'entier supérieur le plus proche. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Détermine si l'objet actuel et l'objet spécifié sont égaux, c’est-à-dire s’ils représentent la même paire de valeurs de largeur et de hauteur. |
| int [get_Height](./get_height/)() const | Renvoie la valeur de hauteur représentée par l'objet actuel. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Détermine si les valeurs de largeur et de hauteur sont toutes deux égales à 0. |
| int [get_Width](./get_width/)() const | Renvoie la valeur de largeur représentée par l'objet actuel. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
|  [operator Point](./operator_point/)() const | Construit une instance de l'objet [Point](../point/) et initialise ses coordonnées X et Y avec les valeurs de largeur et de hauteur de l'objet actuel respectivement. |
|  [operator SizeF](./operator_sizef/)() const | Construit une instance de l'objet [SizeF](../sizef/) et l'initialise avec les valeurs de largeur et de hauteur de l'objet [Size](./) actuel. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Construit un objet [Size](./) à partir de l'objet [SizeF](../sizef/) spécifié en arrondissant les valeurs de largeur et de hauteur de l'objet [SizeF](../sizef/) à l'entier le plus proche. |
| void [set_Height](./set_height/)(int) | Définit la valeur de hauteur représentée par l'objet actuel. |
| void [set_Width](./set_width/)(int) | Définit la valeur de largeur représentée par l'objet actuel. |
|  [Size](./size/)() | Construit un nouvel objet [Size](./) et initialise ses valeurs de largeur et de hauteur à 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Construit un nouvel objet [Size](./) et initialise ses valeurs de largeur et de hauteur avec les valeurs des coordonnées X et Y du point spécifié respectivement. |
|  [Size](./size/)(int, int) | Construit un nouvel objet [Size](./) et l'initialise avec la valeur spécifiée. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Renvoie un nouvel objet [Size](./) qui est le résultat de la soustraction de **size2** à partir de **size1**, c’est-à-dire dont la valeur de largeur est le résultat de la soustraction de la valeur de largeur de **size2** de la valeur de largeur de **size1** et dont la valeur de hauteur est le résultat de la soustraction de la valeur de hauteur de **size2** de la valeur de hauteur de **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de la paire de valeurs de largeur et de hauteur représentée par l'objet actuel. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Construit un objet [Size](./) à partir de l'objet [SizeF](../sizef/) spécifié en tronquant les valeurs de largeur et de hauteur de l'objet [SizeF](../sizef/) à l'entier inférieur le plus proche. |

## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Une instance vide de la classe [Size](./) dont les valeurs de largeur et de hauteur sont 0. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)