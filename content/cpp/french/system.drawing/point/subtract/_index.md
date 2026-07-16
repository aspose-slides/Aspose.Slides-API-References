---
title: Subtract()
second_title: Référence de l'API Aspose.Slides pour C++
description: Soustrait les valeurs de largeur et de hauteur de l'objet Size spécifié des valeurs des coordonnées X et Y de l'objet Point spécifié, respectivement.
type: docs
weight: 196
url: /fr/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) méthode

Soustrait les valeurs de largeur et de hauteur de l'objet [Size](../../size/) spécifié des valeurs des coordonnées X et Y de l'objet [Point](../) spécifié, respectivement.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | Le **point** à translater |
| size | const [Size](../../size/)\& | L'objet [Size](../../size/) qui spécifie les valeurs à soustraire des valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [Point](../) dont la valeur de la coordonnée X est égale au résultat de la soustraction de la valeur de largeur de **size** à la valeur de la coordonnée X de **point** et dont la valeur de la coordonnée Y est égale au résultat de la soustraction de la valeur de hauteur de **size** à la valeur de la coordonnée Y de **point**.

## Voir aussi

* Classe [Point](../)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)