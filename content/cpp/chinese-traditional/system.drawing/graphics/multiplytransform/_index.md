---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API 參考文件
description: 將目前 Graphics 物件的世界變換矩陣乘以指定的矩陣。
type: docs
weight: 872
url: /zh-hant/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) 方法

將目前 [Graphics](../) 物件的世界變換矩陣乘以指定的矩陣。

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 要將目前 [Graphics](../) 物件的世界變換矩陣相乘的矩陣 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 乘法順序 |

## 另請參閱

* Enum [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 類別 [Graphics](../)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)