---
title: Remove
second_title: Referencia de la API Aspose.Slides para .NET
description: Elimina el diseño de la presentación.
type: docs
weight: 90
url: /es/aspose.slides/layoutslide/remove/
---

## Método LayoutSlide.Remove

Elimina el diseño de la presentación.

```csharp
public void Remove()
```

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si el diseño ya ha sido eliminado de la presentación o si el diseño está en uso en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

Para evitar lanzar la PptxEditException, verifique la propiedad HasDependingSlides del diseño primero.

### Ver También

* clase [LayoutSlide](../../layoutslide)
* espacio de nombres [Aspose.Slides](../../layoutslide)
* ensamblado [Aspose.Slides](../../../)