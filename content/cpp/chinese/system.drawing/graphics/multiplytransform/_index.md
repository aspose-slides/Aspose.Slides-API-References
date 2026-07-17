---
title: MultiplyTransform()
second_title: Aspose.Slides C++ API 参考
description: 将当前 Graphics 对象的世界变换矩阵乘以指定的矩阵。
type: docs
weight: 872
url: /zh/system.drawing/graphics/multiplytransform/
---
## Graphics::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) 方法

将当前 [Graphics](../) 对象的世界变换矩阵乘以指定的矩阵。

```cpp
void System::Drawing::Graphics::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 用于将当前 [Graphics](../) 对象的世界变换矩阵相乘的矩阵 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 乘法顺序 |

## 参见

* 枚举 [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 类 [Graphics](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)