---
title: SetGeometryPath
second_title: Aspose.Sildes para .NET Referencia de API
description: Actualiza la geometría de la forma a partir del objeto IGeometryPathaspose.slides/igeometrypath. Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ShapeTypeaspose.slides/geometryshape/shapetype a Personalizado.
type: docs
weight: 60
url: /es/aspose.slides/geometryshape/setgeometrypath/
---

## GeometryShape.SetGeometryPath método

Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](../../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../shapetype)) a Personalizado.

```csharp
public void SetGeometryPath(IGeometryPath geometryPath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPath | IGeometryPath | Ruta de geometría |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | No se encontró la ruta |
| ArgumentException | Se encontró una ruta vacía |

### Ejemplos

Ejemplo:

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

### Ver También

* interfaz [IGeometryPath](../../igeometrypath)
* clase [GeometryShape](../../geometryshape)
* espacio de nombres [Aspose.Slides](../../geometryshape)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->