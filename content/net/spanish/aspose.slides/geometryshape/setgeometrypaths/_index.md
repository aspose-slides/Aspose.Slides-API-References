---
title: SetGeometryPaths
second_title: Referencia API de Aspose.Slides para .NET
description: Actualiza la geometría de la forma a partir de un array de IGeometryPathaspose.slides/igeometrypath. Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ShapeTypeaspose.slides/geometryshape/shapetype a Personalizado.
type: docs
weight: 70
url: /es/aspose.slides/geometryshape/setgeometrypaths/
---

## GeometryShape.SetGeometryPaths method

Actualiza la geometría de la forma a partir de un array de [`IGeometryPath`](../../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../shapetype)) a Personalizado.

```csharp
public void SetGeometryPaths(IGeometryPath[] geometryPaths)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPaths | IGeometryPath[] | Array de caminos de geometría |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | No se encontró el camino |
| ArgumentException | Camino vacío |

### Ejemplos

Ejemplo:

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

### Ver También

* interfaz [IGeometryPath](../../igeometrypath)
* clase [GeometryShape](../../geometryshape)
* espacio de nombres [Aspose.Slides](../../geometryshape)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITE: generado por xmldocmd para Aspose.Slides.dll -->