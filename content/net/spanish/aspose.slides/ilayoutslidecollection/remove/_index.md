---
title: Eliminar
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina un diseño de la colección.
type: docs
weight: 30
url: /es/aspose.slides/ilayoutslidecollection/remove/
---

## Método ILayoutSlideCollection.Remove

Elimina un diseño de la colección.

```csharp
public void Remove(ILayoutSlide value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | ILayoutSlide | El diseño a eliminar de la colección. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzada si el diseño se utiliza en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar lanzar la PptxEditException, verifica la propiedad HasDependingSlides del diseño antes. 2) También puedes usar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Véase también

* interfaz [ILayoutSlide](../../ilayoutslide)
* interfaz [ILayoutSlideCollection](../../ilayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../ilayoutslidecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->