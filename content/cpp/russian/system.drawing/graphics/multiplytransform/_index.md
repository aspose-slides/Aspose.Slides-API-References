---
title: MultiplyTransform()
second_title: Aspose.Slides для C++ справочник API
description: Умножает мировую матрицу преобразования текущего объекта Graphics на указанную матрицу.
type: docs
weight: 872
url: /ru/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) метод

Умножает мировую матрицу преобразования текущего [Graphics](../) объекта на указанную матрицу.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | Матрица, которой умножается мировая матрица преобразования текущего [Graphics](../) объекта |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | Порядок умножения |

## См. также

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../../../system.drawing.drawing2d/matrix/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)