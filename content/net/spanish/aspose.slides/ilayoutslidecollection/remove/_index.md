---
title: Remove
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina un diseño de la colección.
type: docs
weight: 30
url: /es/aspose.slides/ilayoutslidecollection/remove/
---

## ILayoutSlideCollection.Remove método

Elimina un diseño de la colección.

```csharp
public void Remove(ILayoutSlide value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | ILayoutSlide | El diseño que se va a eliminar de la colección. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si el diseño está utilizado en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar el lanzamiento de la PptxEditException, verifique la propiedad HasDependingSlides del diseño antes. 2) También puede utilizar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* interfaz [ILayoutSlideCollection](../../ilayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../ilayoutslidecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->