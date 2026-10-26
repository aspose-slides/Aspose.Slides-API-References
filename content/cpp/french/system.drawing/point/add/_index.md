---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute les valeurs de largeur et de hauteur de l'objet Size spécifié aux valeurs des coordonnées X et Y de l'objet Point spécifié, respectivement.
type: docs
weight: 183
url: /fr/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) méthode

Ajoute les valeurs de largeur et de hauteur de l'objet [Size](../../size/) spécifié aux valeurs des coordonnées X et Y de l'objet [Point](../) spécifié, respectivement.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | Le point à translater |
| size | const [Size](../../size/)\& | L'objet [Size](../../size/) qui spécifie les valeurs à ajouter aux valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [Point](../) dont la valeur de la coordonnée X est égale à la somme de la valeur de la coordonnée X du **point** et de la valeur de largeur du **size**, et dont la valeur de la coordonnée Y est égale à la somme de la valeur de la coordonnée Y du **point** et de la valeur de hauteur du **size**

## Voir aussi

* Classe [Point](../)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)