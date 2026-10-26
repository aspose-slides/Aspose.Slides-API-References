---
title: FillPolygon()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的画笔填充指定多边形的内部。
type: docs
weight: 417
url: /zh/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) method

使用指定的画笔填充指定多边形的内部。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 一个 [Brush](../../brush/) 对象，指定填充的参数 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 包含定义多边形的点的数组 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 填充模式 |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) method

使用指定的画笔填充指定多边形的内部。

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 一个 [Brush](../../brush/) 对象，指定填充的参数 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 包含定义多边形的点的数组 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 填充模式 |

## 另见

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)