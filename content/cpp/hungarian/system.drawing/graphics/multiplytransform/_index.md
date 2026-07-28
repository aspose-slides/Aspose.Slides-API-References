---
title: MultiplyTransform()
second_title: Aspose.Slides C++ API referenciája
description: Megszorozza a jelenlegi Graphics objektum világtranszformációs mátrixát a megadott mátrixszal.
type: docs
weight: 872
url: /hu/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) metódus


Megszorozza a jelenlegi [Graphics](../) objektum világtranszformációs mátrixát a megadott mátrixszal.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | A mátrix, amelynek segítségével a jelenlegi [Graphics](../) objektum világtranszformációs mátrixát megszorozzuk |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | A szorzás sorrendje |

## Lásd még

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Matrix](../../../system.drawing.drawing2d/matrix/)
* Osztály [Graphics](../)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)