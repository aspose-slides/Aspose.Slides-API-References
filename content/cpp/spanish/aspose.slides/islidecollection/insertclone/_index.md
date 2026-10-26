---
title: InsertClone()
second_title: Aspose.Slides para C++ Referencia de API
description: Inserta una copia de una diapositiva especificada en la posición especificada de la colección.
type: docs
weight: 27
url: /es/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) método


Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |

### Valor de retorno

Diapositiva insertada.
## Observaciones



Al clonar una diapositiva entre distintas presentaciones, el master de la diapositiva también puede clonarse. Se utiliza un registro interno para rastrear los masters clonados automáticamente y evitar la creación de múltiples clones del mismo master de diapositiva. La clonación manual de masters de diapositivas no será ni impedida ni registrada. Si necesita más control sobre el proceso de clonación, utilice [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) o [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) para clonar diapositivas y [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar masters. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) método


Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositiva de diseño para una nueva diapositiva. |

### Valor de retorno

Diapositiva insertada.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) método


Inserta una copia de una diapositiva origen especificada en la posición especificada de la colección. Se seleccionará automáticamente un diseño apropiado del master especificado (un diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva origen). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva origen (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva master para una nueva diapositiva. |
| allowCloneMissingLayout | **bool** | Si no hay un diseño apropiado en el master especificado, entonces se clonará el diseño de la diapositiva origen (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

### Valor de retorno

Diapositiva insertada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [ISlideCollection](../)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IMasterSlide](../../imasterslide/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)