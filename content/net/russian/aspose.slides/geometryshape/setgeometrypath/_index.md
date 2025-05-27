---
title: SetGeometryPath
second_title: Aspose.Slides для .NET API Reference
description: Обновляет геометрию фигуры из объекта IGeometryPathaspose.slides/igeometrypath. Координаты должны быть относительными к левому верхнему углу фигуры. Изменяет тип фигуры ShapeTypeaspose.slides/geometryshape/shapetype на Пользовательский.
type: docs
weight: 60
url: /ru/aspose.slides/geometryshape/setgeometrypath/
---

## GeometryShape.SetGeometryPath метод

Обновляет геометрию фигуры из объекта [`IGeometryPath`](../../igeometrypath). Координаты должны быть относительными к левому верхнему углу фигуры. Изменяет тип фигуры ([`ShapeType`](../shapetype)) на Пользовательский.

```csharp
public void SetGeometryPath(IGeometryPath geometryPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometryPath | IGeometryPath | Путь геометрии |

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

### Смотрите также

* интерфейс [IGeometryPath](../../igeometrypath)
* класс [GeometryShape](../../geometryshape)
* пространство имен [Aspose.Slides](../../geometryshape)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->