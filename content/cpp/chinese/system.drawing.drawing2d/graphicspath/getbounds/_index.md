---
title: GetBounds()
second_title: Aspose.Slides C++ API 参考
description: 返回一个 RectangleF 对象，表示在使用指定矩阵进行变换时，当前对象所表示的路径的边界矩形。
type: docs
weight: 339
url: /zh/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const 方法

返回一个 [RectangleF](../../../system.drawing/rectanglef/) 对象，表示在使用指定矩阵进行变换时，当前对象所表示的路径的边界矩形。

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 变换矩阵 |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | 用于计算边界矩形的 [Pen](../../../system.drawing/pen/) |

## 另请参阅

* 类型定义 [MatrixPtr](../../matrixptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 类 [Pen](../../../system.drawing/pen/)
* 类 [GraphicsPath](../)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)