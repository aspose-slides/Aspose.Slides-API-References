---
title: Remove
second_title: Referencia de la API Aspose.Slides para .NET
description: Elimina el diseño de la presentación.
type: docs
weight: 90
url: /es/aspose.slides/ilayoutslide/remove/
---

## Método ILayoutSlide.Remove

Elimina el diseño de la presentación.

```csharp
public void Remove()
```

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzada si el diseño ya ha sido eliminado de la presentación o si el diseño está en uso en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

Para evitar lanzar la PptxEditException, verifica la propiedad HasDependingSlides del diseño previamente.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* espacio de nombres [Aspose.Slides](../../ilayoutslide)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->