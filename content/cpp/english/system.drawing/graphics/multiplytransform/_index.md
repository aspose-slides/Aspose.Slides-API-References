---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API Reference
description: Multiplies the world transformation matrix of the current Graphics object by the specified matrix.
type: docs
weight: 872
url: /system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) method


Multiplies the world transformation matrix of the current [Graphics](../) object by the specified matrix.

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | The matrix to multiply the world transformation matrix of the current [Graphics](../) object by |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | The multiplication order |

## See Also

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Matrix](../../../system.drawing.drawing2d/matrix/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)