---
title: Subtract()
second_title: Référence API Aspose.Slides pour C++
description: Soustrait les valeurs de largeur et de hauteur de l'objet SizeF spécifié des valeurs des coordonnées X et Y de l'objet PointF spécifié, respectivement.
type: docs
weight: 157
url: /fr/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) method

Soustrait les valeurs de largeur et de hauteur de l'objet [SizeF](../../sizef/) spécifié des valeurs des coordonnées X et Y de l'objet [PointF](../) spécifié, respectivement.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Le point à traduire |
| size | const [SizeF](../../sizef/)\& | L'objet [SizeF](../../sizef/) qui spécifie les valeurs à soustraire des valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [PointF](../) dont la valeur de la coordonnée X est égale au résultat de la soustraction de la valeur de largeur de **size** à la valeur de la coordonnée X de **point** et dont la valeur de la coordonnée Y est égale au résultat de la soustraction de la valeur de hauteur de **size** à la valeur de la coordonnée Y de **point**

## PointF::Subtract(const PointF\&, const Size\&) method

Soustrait les valeurs de largeur et de hauteur de l'objet [Size](../../size/) spécifié des valeurs des coordonnées X et Y de l'objet [PointF](../) spécifié, respectivement.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Le point à traduire |
| size | const [Size](../../size/)\& | L'objet [Size](../../size/) qui spécifie les valeurs à soustraire des valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [PointF](../) dont la valeur de la coordonnée X est égale au résultat de la soustraction de la valeur de largeur de **size** à la valeur de la coordonnée X de **point** et dont la valeur de la coordonnée Y est égale au résultat de la soustraction de la valeur de hauteur de **size** à la valeur de la coordonnée Y de **point**

## Voir aussi

* Classe [PointF](../)
* Classe [SizeF](../../sizef/)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)