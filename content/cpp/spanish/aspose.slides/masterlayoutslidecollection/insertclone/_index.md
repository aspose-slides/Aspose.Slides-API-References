---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una copia de una diapositiva de diseño especificada en la posición indicada de la colección.
type: docs
weight: 14
url: /es/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) método

Inserta una copia de una diapositiva de diseño especificada en la posición indicada de la colección.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva insertada.

## Observaciones

El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diseños de diapositivas. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [MasterLayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)