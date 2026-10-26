---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute les valeurs de largeur et de hauteur de l'objet SizeF spécifié aux valeurs des coordonnées X et Y de l'objet PointF spécifié, respectivement.
type: docs
weight: 144
url: /fr/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) méthode

Ajoute les valeurs de largeur et de hauteur de l'objet [SizeF](../../sizef/) spécifié aux valeurs des coordonnées X et Y de l'objet [PointF](../) spécifié, respectivement.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Le point à traduire |
| size | const [SizeF](../../sizef/)\& | L'objet [SizeF](../../sizef/) qui spécifie les valeurs à ajouter aux valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [PointF](../) dont la valeur de la coordonnée X est égale à la somme de la valeur de la coordonnée X du **point** et de la valeur de la largeur du **size**, et dont la valeur de la coordonnée Y est égale à la somme de la valeur de la coordonnée Y du **point** et de la valeur de la hauteur du **size**.

## PointF::Add(const PointF\&, const Size\&) méthode

Ajoute les valeurs de largeur et de hauteur de l'objet [Size](../../size/) spécifié aux valeurs des coordonnées X et Y de l'objet [PointF](../) spécifié, respectivement.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | Le point à traduire |
| size | const [Size](../../size/)\& | L'objet [Size](../../size/) qui spécifie les valeurs à ajouter aux valeurs des coordonnées du **point** |

### Valeur de retour

Un nouvel objet [PointF](../) dont la valeur de la coordonnée X est égale à la somme de la valeur de la coordonnée X du **point** et de la valeur de la largeur du **size**, et dont la valeur de la coordonnée Y est égale à la somme de la valeur de la coordonnée Y du **point** et de la valeur de la hauteur du **size**.

## Voir aussi

* Classe [PointF](../)
* Classe [SizeF](../../sizef/)
* Classe [Size](../../size/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)