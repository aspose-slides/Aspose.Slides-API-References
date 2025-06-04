---
title: SetGeometryPaths
second_title: Aspose.Slides para .NET API Reference
description: Actualiza la geometría de la forma a partir de un array de IGeometryPathaspose.slides/igeometrypath. Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ShapeTypeaspose.slides/igeometryshape/shapetype a Personalizada.
type: docs
weight: 80
url: /es/aspose.slides/igeometryshape/setgeometrypaths/
---

## IGeometryShape.SetGeometryPaths método

Actualiza la geometría de la forma a partir de un array de [`IGeometryPath`](../../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../shapetype)) a Personalizada.

```csharp
public void SetGeometryPaths(IGeometryPath[] geometryPaths)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPaths | IGeometryPath[] | Array de rutas de geometría |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | No se encontró ninguna ruta |
| ArgumentException | Ruta vacía |

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
* interfaz [IGeometryShape](../../igeometryshape)
* espacio de nombres [Aspose.Slides](../../igeometryshape)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->