---
title: MultiplyTransform()
second_title: Aspose.Slides für C++ API Referenz
description: Multipliziert die Welt-Transformationsmatrix des aktuellen Graphics-Objekts mit der angegebenen Matrix.
type: docs
weight: 872
url: /de/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) Methode


Multipliziert die Welt-Transformationsmatrix des aktuellen [Graphics](../)-Objekts mit der angegebenen Matrix.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | Die Matrix, mit der die Welt-Transformationsmatrix des aktuellen [Graphics](../)-Objekts multipliziert wird |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | Die Multiplikationsreihenfolge |

## Siehe auch

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Matrix](../../../system.drawing.drawing2d/matrix/)
* Klasse [Graphics](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)