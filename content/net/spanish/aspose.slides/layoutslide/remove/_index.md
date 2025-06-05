---
title: Remove
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina el diseño de la presentación.
type: docs
weight: 90
url: /es/aspose.slides/layoutslide/remove/
---

## LayoutSlide.Remove método

Elimina el diseño de la presentación.

```csharp
public void Remove()
```

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzada si el diseño ya ha sido eliminado de la presentación o si el diseño está siendo utilizado en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

Para evitar lanzar la PptxEditException, verifica la propiedad HasDependingSlides del diseño primero.

### Véase También

* clase [LayoutSlide](../../layoutslide)
* espacio de nombres [Aspose.Slides](../../layoutslide)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->