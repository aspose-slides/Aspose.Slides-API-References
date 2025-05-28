---
title: DrawingGuides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve la colección de las guías de dibujo. Solo lectura IDrawingGuidesCollectionaspose.slides/idrawingguidescollection
type: docs
weight: 10
url: /es/aspose.slides/commonslideviewproperties/drawingguides/
---

## Propiedad CommonSlideViewProperties.DrawingGuides

Devuelve la colección de las guías de dibujo. Solo lectura [`IDrawingGuidesCollection`](../../idrawingguidescollection)

```csharp
public IDrawingGuidesCollection DrawingGuides { get; }
```

### Ejemplos

El siguiente código de ejemplo muestra cómo agregar las nuevas guías de dibujo en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    var slideSize = pres.SlideSize.Size;
    
    IDrawingGuidesCollection guides = pres.ViewProperties.SlideViewProperties.DrawingGuides;
    // Agregando la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
    guides.Add(Orientation.Vertical, slideSize.Width / 2 + 12.5f);
    // Agregando la nueva guía de dibujo horizontal debajo del centro de la diapositiva
    guides.Add(Orientation.Horizontal, slideSize.Height / 2 + 12.5f);
    
    pres.Save("DrawingGuides_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IDrawingGuidesCollection](../../idrawingguidescollection)
* clase [CommonSlideViewProperties](../../commonslideviewproperties)
* espacio de nombres [Aspose.Slides](../../commonslideviewproperties)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->