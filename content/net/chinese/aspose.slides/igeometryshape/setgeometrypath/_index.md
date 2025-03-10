---
title: SetGeometryPath
second_title: Aspose.Slides for .NET API 参考
description: 从IGeometryPathaspose.slides/igeometrypath对象更新形状几何坐标必须相对于形状的左 上角 将形状的类型ShapeTypeaspose.slides/igeometryshape/shapetype更改为Custom.
type: docs
weight: 70
url: /zh/aspose.slides/igeometryshape/setgeometrypath/
---
## IGeometryShape.SetGeometryPath method

从[`IGeometryPath`](../../igeometrypath)对象更新形状几何。坐标必须相对于形状的左 上角。 将形状的类型（[`ShapeType`](../shapetype)）更改为Custom.

```csharp
public void SetGeometryPath(IGeometryPath geometryPath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| geometryPath | IGeometryPath | 几何路径 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 否找到路径 |
| ArgumentException | 找到空路径 |

### 例子

示例:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    GeometryShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 200, 100) as GeometryShape;

    GeometryPath geometryPath0 = new GeometryPath();
    geometryPath0.MoveTo(0, 0);
    geometryPath0.LineTo(shape.Width, 0);
    geometryPath0.LineTo(shape.Width, shape.Height/3);
    geometryPath0.LineTo(0, shape.Height / 3);
    geometryPath0.CloseFigure();

    GeometryPath geometryPath1 = new GeometryPath();
    geometryPath1.MoveTo(0, shape.Height/3 * 2);
    geometryPath1.LineTo(shape.Width, shape.Height / 3 * 2);
    geometryPath1.LineTo(shape.Width, shape.Height);
    geometryPath1.LineTo(0, shape.Height);
    geometryPath1.CloseFigure();

    shape.SetGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});

    pres.Save("output.pptx", SaveFormat.Pptx);
}
```

### 也可以看看

* interface [IGeometryPath](../../igeometrypath)
* interface [IGeometryShape](../../igeometryshape)
* 命名空间 [Aspose.Slides](../../igeometryshape)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
