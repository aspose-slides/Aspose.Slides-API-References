---
title: GetGeometryPaths
second_title: Справочник по API Aspose.Slides для .NET
description: Возвращает копию пути геометрической фигуры. Координаты относятся к левому верхнему углу фигуры.
type: docs
weight: 60
url: /ru/net/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape.GetGeometryPaths method

Возвращает копию пути геометрической фигуры. Координаты относятся к левому верхнему углу фигуры.

```csharp
public IGeometryPath[] GetGeometryPaths()
```

### Возвращаемое значение

Массив[`IGeometryPath`](../../igeometrypath)

### Примеры

Пример:

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

### Смотрите также

* interface [IGeometryPath](../../igeometrypath)
* interface [IGeometryShape](../../igeometryshape)
* пространство имен [Aspose.Slides](../../igeometryshape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->