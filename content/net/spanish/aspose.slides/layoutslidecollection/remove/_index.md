---
title: Eliminar
second_title: Referencia de API de Aspose.Sildes para .NET
description: Elimina un diseño de la colección.
type: docs
weight: 80
url: /es/aspose.slides/layoutslidecollection/remove/
---

## Método LayoutSlideCollection.Remove

Elimina un diseño de la colección.

```csharp
public void Remove(ILayoutSlide value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | ILayoutSlide | El diseño que se eliminará de la colección. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Se lanza si el diseño se utiliza en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar lanzar la PptxEditException, verifica la propiedad HasDependingSlides del diseño antes. 2) También puedes usar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* clase [LayoutSlideCollection](../../layoutslidecollection)
* espacio de nombres [Aspose.Slides](../../layoutslidecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->