---
title: GeometryPath
second_title: Aspose.Slides for .NET API 参考
description: 表示 GeometryShape 的几何路径
type: docs
weight: 4500
url: /zh/net/aspose.slides/geometrypath/
---
## GeometryPath class

表示 GeometryShape 的几何路径

```csharp
public sealed class GeometryPath : IGeometryPath
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GeometryPath](geometrypath)() | 创建 GeometryPath 的实例 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FillMode](../../aspose.slides/geometrypath/fillmode) { get; set; } | 设置填充模式 |
| [PathData](../../aspose.slides/geometrypath/pathdata) { get; } | 以路径段数组的形式返回 GeometryShape 的几何路径。 |
| [Stroke](../../aspose.slides/geometrypath/stroke) { get; set; } | 设置笔触外观 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ArcTo](../../aspose.slides/geometrypath/arcto)(float, float, float, float) | 将指定的弧附加到路径。 |
| [CloseFigure](../../aspose.slides/geometrypath/closefigure)() | 关闭当前路径 |
| [CubicBezierTo](../../aspose.slides/geometrypath/cubicbezierto#cubicbezierto_2)(PointF, PointF, PointF) | 在路径末尾添加三次贝塞尔曲线 |
| [CubicBezierTo](../../aspose.slides/geometrypath/cubicbezierto#cubicbezierto_3)(PointF, PointF, PointF, uint) | 将三次贝塞尔曲线添加到路径的指定位置 |
| [CubicBezierTo](../../aspose.slides/geometrypath/cubicbezierto#cubicbezierto)(float, float, float, float, float, float) | 在路径末尾添加三次贝塞尔曲线 |
| [CubicBezierTo](../../aspose.slides/geometrypath/cubicbezierto#cubicbezierto_1)(float, float, float, float, float, float, uint) | 将三次贝塞尔曲线添加到路径的指定位置 |
| [LineTo](../../aspose.slides/geometrypath/lineto#lineto_2)(PointF) | 在路径末尾添加行 |
| [LineTo](../../aspose.slides/geometrypath/lineto#lineto)(float, float) | 在路径末尾添加一行 |
| [LineTo](../../aspose.slides/geometrypath/lineto#lineto_3)(PointF, uint) | 将行添加到路径的指定位置 |
| [LineTo](../../aspose.slides/geometrypath/lineto#lineto_1)(float, float, uint) | 将行添加到路径的指定位置 |
| [MoveTo](../../aspose.slides/geometrypath/moveto#moveto_1)(PointF) | 设置下一个点的位置。 |
| [MoveTo](../../aspose.slides/geometrypath/moveto#moveto)(float, float) | 设置下一个点的位置。 |
| [QuadraticBezierTo](../../aspose.slides/geometrypath/quadraticbezierto#quadraticbezierto_2)(PointF, PointF) | 在路径末尾添加二次贝塞尔曲线 |
| [QuadraticBezierTo](../../aspose.slides/geometrypath/quadraticbezierto#quadraticbezierto_3)(PointF, PointF, uint) | 将二次贝塞尔曲线添加到路径的指定位置 |
| [QuadraticBezierTo](../../aspose.slides/geometrypath/quadraticbezierto#quadraticbezierto)(float, float, float, float) | 在路径末尾添加二次贝塞尔曲线 |
| [QuadraticBezierTo](../../aspose.slides/geometrypath/quadraticbezierto#quadraticbezierto_1)(float, float, float, float, uint) | 将二次贝塞尔曲线添加到路径的指定位置 |
| [RemoveAt](../../aspose.slides/geometrypath/removeat)(int) | 删除几何路径指定索引处的段。 |

### 也可以看看

* interface [IGeometryPath](../igeometrypath)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->