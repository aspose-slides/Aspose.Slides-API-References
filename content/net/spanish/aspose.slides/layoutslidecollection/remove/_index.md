---
title: Remove
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina un diseño de la colección.
type: docs
weight: 80
url: /es/aspose.slides/layoutslidecollection/remove/
---

## LayoutSlideCollection.Remove método

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
| [PptxEditException](../../pptxeditexception) | Se lanza si el diseño se usa en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar lanzar la PptxEditException, comprueba la propiedad HasDependingSlides del diseño primero. 2) También puedes usar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* clase [LayoutSlideCollection](../../layoutslidecollection)
* espacio de nombres [Aspose.Slides](../../layoutslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->