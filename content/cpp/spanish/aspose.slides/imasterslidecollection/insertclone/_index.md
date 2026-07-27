---
title: InsertClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.
type: docs
weight: 66
url: /es/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) método

Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) para clonar. |

### Return Value

Diapositiva maestra insertada.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMasterSlide](../../imasterslide/)
* Clase [IMasterSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)