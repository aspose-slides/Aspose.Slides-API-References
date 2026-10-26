---
title: MultiplyTransform()
second_title: Aspose.Slides för C++ API-referens
description: Multiplicerar världstransformationsmatrisen för det aktuella Graphics-objektet med den angivna matrisen.
type: docs
weight: 872
url: /sv/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) metod


Multiplicerar världstransformationsmatrisen för det aktuella [Graphics](../)-objektet med den angivna matrisen.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | Matrisen som ska multipliceras med världstransformationsmatrisen för det aktuella [Graphics](../)-objektet |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | Multiplikationsordningen |

## Se även

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Matrix](../../../system.drawing.drawing2d/matrix/)
* Klass [Graphics](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)