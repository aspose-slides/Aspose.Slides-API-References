---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的笔绘制封闭的样条曲线。
type: docs
weight: 781
url: /zh/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) 方法

绘制使用指定笔的封闭样条线。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 绘制样条线时使用的笔 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 用于确定样条线的[Array](../../../system/array/)点 |
| tension | **float** | 指定样条线张力的值 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) 方法

绘制使用指定笔的封闭样条线。

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 绘制样条线时使用的笔 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 用于确定样条线的[Array](../../../system/array/)点 |
| tension | **float** | 指定样条线张力的值 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 已忽略 |

## 参见

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)