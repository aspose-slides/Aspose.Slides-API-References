---
title: LayoutSlideCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una clase base para la colección de diapositivas de diseño.
type: docs
weight: 7410
url: /es/aspose.slides/layoutslidecollection/
---

## Clase LayoutSlideCollection

Representa una clase base para la colección de diapositivas de diseño.

```csharp
public class LayoutSlideCollection : ILayoutSlideCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/layoutslidecollection/count) { get; } | Devuelve el número de diapositivas de diseño en una colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/layoutslidecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/layoutslidecollection/item) { get; } | Devuelve la diapositiva de diseño por índice. Solo lectura [`LayoutSlide`](../layoutslide). |
| [SyncRoot](../../aspose.slides/layoutslidecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyTo](../../aspose.slides/layoutslidecollection/copyto)(Array, int) | Copia todos los elementos de la colección al arreglo especificado. |
| [GetByType](../../aspose.slides/layoutslidecollection/getbytype)(SlideLayoutType) | Devuelve la primera diapositiva de diseño del tipo especificado. Un tipo de diapositiva de diseño a encontrar. [`LayoutSlide`](../layoutslide) con el tipo especificado o nulo si no se encontraron diseños. |
| [GetEnumerator](../../aspose.slides/layoutslidecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../aspose.slides/layoutslidecollection/remove)(ILayoutSlide) | Elimina una diapositiva de diseño de la colección. |
| [RemoveUnused](../../aspose.slides/layoutslidecollection/removeunused)() | Elimina las diapositivas de diseño no utilizadas (diapositivas de diseño cuyo HasDependingSlides es falso). |

### Vea También

* interfaz [ILayoutSlideCollection](../ilayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->