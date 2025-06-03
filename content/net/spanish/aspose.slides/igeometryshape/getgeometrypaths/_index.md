---
title: GetGeometryPaths
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve la copia de la ruta de la forma de geometría. Las coordenadas son relativas a la esquina superior izquierda de la forma.
type: docs
weight: 60
url: /es/aspose.slides/igeometryshape/getgeometrypaths/
---

## IGeometryShape.GetGeometryPaths método

Devuelve la copia de la ruta de la forma de geometría. Las coordenadas son relativas a la esquina superior izquierda de la forma.

```csharp
public IGeometryPath[] GetGeometryPaths()
```

### Valor de Retorno

Array de [`IGeometryPath`](../../igeometrypath)

### Ejemplos

Ejemplo:

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

### Véase También

* interfaz [IGeometryPath](../../igeometrypath)
* interfaz [IGeometryShape](../../igeometryshape)
* espacio de nombres [Aspose.Slides](../../igeometryshape)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->