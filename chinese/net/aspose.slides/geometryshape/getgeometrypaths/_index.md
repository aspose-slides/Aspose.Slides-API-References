---
title: GetGeometryPaths
second_title: Aspose.Slides for .NET API 参考
description: 返回几何形状路径的副本 坐标相对于形状的左上角
type: docs
weight: 50
url: /zh/net/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape.GetGeometryPaths method

返回几何形状路径的副本。 坐标相对于形状的左上角。

```csharp
public IGeometryPath[] GetGeometryPaths()
```

### 返回值

[`IGeometryPath`](../../igeometrypath)

### 例子

示例:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    GeometryShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 200, 100) as GeometryShape;

    IGeometryPath geometryPath = shape.GetGeometryPaths()[0];

    geometryPath.LineTo(100, 50, 1);
    geometryPath.LineTo(100, 50, 4);

    shape.SetGeometryPath(geometryPath);

    pres.Save("output.pptx", SaveFormat.Pptx);
}
```

### 也可以看看

* interface [IGeometryPath](../../igeometrypath)
* class [GeometryShape](../../geometryshape)
* 命名空间 [Aspose.Slides](../../geometryshape)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->