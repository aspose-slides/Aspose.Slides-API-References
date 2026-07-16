---
title: GetBounds()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un objet RectangleF qui représente un rectangle englobant le chemin représenté par l'objet actuel lorsqu'il est transformé avec la matrice spécifiée.
type: docs
weight: 339
url: /fr/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr&, const SharedPtr<Pen>&) const méthode

Renvoie un objet [RectangleF](../../../system.drawing/rectanglef/) qui représente un rectangle qui englobe le chemin représenté par l'objet actuel lorsqu'il est transformé avec la matrice spécifiée.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)& | La matrice de transformation |
| pen | const [SharedPtr](../../../system/sharedptr/)<[Pen](../../../system.drawing/pen/)>& | Un [Pen](../../../system.drawing/pen/) pour calculer le rectangle englobant. |

## Voir aussi

* Typedef [MatrixPtr](../../matrixptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Pen](../../../system.drawing/pen/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)