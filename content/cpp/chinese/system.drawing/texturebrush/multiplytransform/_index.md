---
title: MultiplyTransform()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象的变换矩阵乘以指定的矩阵。
type: docs
weight: 144
url: /zh/system.drawing/texturebrush/multiplytransform/
---
## TextureBrush::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) 方法

将当前对象的变换矩阵乘以指定的矩阵。

```cpp
void System::Drawing::TextureBrush::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | 用于乘以当前对象的变换矩阵的矩阵 |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | 指定操作的顺序 |

## 另请参见

* 枚举 [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Matrix](../../../system.drawing.drawing2d/matrix/)
* 类 [TextureBrush](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)