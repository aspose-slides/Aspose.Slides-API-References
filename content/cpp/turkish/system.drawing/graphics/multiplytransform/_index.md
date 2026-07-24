---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut Graphics nesnesinin dünya dönüşüm matrisini belirtilen matris ile çarpar.
type: docs
weight: 872
url: /tr/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) metod

Mevcut [Graphics](../) nesnesinin dünya dönüşüm matrisini belirtilen matris ile çarpar.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | Mevcut [Graphics](../) nesnesinin dünya dönüşüm matrisini çarpmak için kullanılan matris |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | Çarpma sırası |

## Bakınız

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Matrix](../../../system.drawing.drawing2d/matrix/)
* Sınıf [Graphics](../)
* İsim Alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)