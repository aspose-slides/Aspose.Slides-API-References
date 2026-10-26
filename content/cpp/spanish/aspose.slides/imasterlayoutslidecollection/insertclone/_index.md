---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una copia de una diapositiva de diseño especificada en la posición especificada de la colección.
type: docs
weight: 14
url: /es/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) método


Inserta una copia de una diapositiva de diseño especificada en la posición especificada de la colección.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva insertada.
## Observaciones



El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IMasterLayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)