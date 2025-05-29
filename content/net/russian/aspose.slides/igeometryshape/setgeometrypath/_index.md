---
title: SetGeometryPath
second_title: Aspose.Slides для .NET API Справочник
description: Обновляет геометрию фигуры из объекта IGeometryPathaspose.slides/igeometrypath. Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ShapeTypeaspose.slides/igeometryshape/shapetype на Custom.
type: docs
weight: 70
url: /ru/aspose.slides/igeometryshape/setgeometrypath/
---

## IGeometryShape.SetGeometryPath метод

Обновляет геометрию фигуры из объекта [`IGeometryPath`](../../igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([`ShapeType`](../shapetype)) на Custom.

```csharp
public void SetGeometryPath(IGeometryPath geometryPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPath | IGeometryPath | Геометрический путь |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Путь не найден |
| ArgumentException | Пустой путь найден |

### Примеры

Пример:

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

### См. Также

* интерфейс [IGeometryPath](../../igeometrypath)
* интерфейс [IGeometryShape](../../igeometryshape)
* пространство имен [Aspose.Slides](../../igeometryshape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->