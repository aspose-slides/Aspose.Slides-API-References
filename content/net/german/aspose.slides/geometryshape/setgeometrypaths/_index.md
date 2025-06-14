---
title: SetGeometryPaths
second_title: Aspose.Sildes für .NET API-Referenz
description: Aktualisiert die Formgeometrie aus einem Array von IGeometryPathaspose.slides/igeometrypath. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ShapeTypeaspose.slides/geometryshape/shapetype auf Benutzerdefiniert.
type: docs
weight: 70
url: /de/aspose.slides/geometryshape/setgeometrypaths/
---

## GeometryShape.SetGeometryPaths Methode

Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](../../igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`ShapeType`](../shapetype)) auf Benutzerdefiniert.

```csharp
public void SetGeometryPaths(IGeometryPath[] geometryPaths)
```

| Parameter      | Typ               | Beschreibung               |
|----------------|-------------------|----------------------------|
| geometryPaths  | IGeometryPath[]   | Array von Geometriepunkten |

### Ausnahmen

| Ausnahme          | Bedingung                  |
|-------------------|----------------------------|
| ArgumentException  | Kein Pfad gefunden         |
| ArgumentException  | Leerer Pfad                |

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    GeometryShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 200, 100) as GeometryShape;

    GeometryPath geometryPath = shape.GetGeometryPaths()[0];

    geometryPath.LineTo(100, 50, 1);
    geometryPath.LineTo(100, 50, 4);

    shape.SetGeometryPath(geometryPath);

    pres.Save("output.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* interface [IGeometryPath](../../igeometrypath)
* class [GeometryShape](../../geometryshape)
* namespace [Aspose.Slides](../../geometryshape)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->