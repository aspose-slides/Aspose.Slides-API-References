---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una copia de una diapositiva especificada en la posición indicada de la colección.
type: docs
weight: 66
url: /es/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) método


Inserta una copia de una diapositiva especificada en la posición indicada de la colección.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) a clonar. |

### Valor devuelto

Diapositiva insertada.
## Observaciones



Al clonar una diapositiva entre presentaciones diferentes también puede clonarse el maestro de la diapositiva. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro de diapositiva. La clonación manual de maestros de diapositiva no será impedida ni registrada. Si necesita un mayor control sobre el proceso de clonación, use [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) o [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) para clonar diapositivas y [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar maestros. 


El siguiente ejemplo muestra cómo clonar en otra posición dentro de [Presentation](../../presentation/). 
```cpp
// Instanciar la clase Presentation que representa un archivo de presentación
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Clonar la diapositiva deseada al final de la colección de diapositivas en la misma presentación
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Clonar la diapositiva deseada al índice especificado en la misma presentación
slides->InsertClone(2, slides->idx_get(1));
// Guardar la presentación modificada en disco
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 El siguiente ejemplo muestra cómo clonar en otra posición dentro de [Presentation](../../presentation/). 
```cpp
// Instanciar la clase Presentation para cargar el archivo de presentación origen
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instanciar la clase Presentation para el PPTX de destino (donde se clonará la diapositiva)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Guardar la presentación de destino en disco
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) método


Inserta una copia de una diapositiva especificada en la posición indicada de la colección.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) a clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositiva de diseño para la nueva diapositiva. |

### Valor devuelto

Diapositiva insertada.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) método


Inserta una copia de una diapositiva origen especificada en la posición indicada de la colección. El diseño apropiado se seleccionará automáticamente del maestro especificado (el diseño apropiado es el que tiene el mismo Tipo o Nombre que el diseño de la diapositiva origen). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva origen (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de la nueva diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) a clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Maestro de diapositiva para la nueva diapositiva. |
| allowCloneMissingLayout | **bool** | Si no hay un diseño apropiado en el maestro especificado, entonces se clonará el diseño de la diapositiva origen (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

### Valor devuelto

Diapositiva insertada.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)