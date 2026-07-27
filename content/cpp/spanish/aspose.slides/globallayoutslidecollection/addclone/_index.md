---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una copia de una diapositiva de diseño especificada a la presentación.
type: docs
weight: 1
url: /es/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva añadida.

## Observaciones

Al clonar un diseño entre presentaciones diferentes, el maestro del diseño también puede clonarse para mantener el formato de origen. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro de diapositiva. La clonación manual de diapositivas maestras no será ni evitada ni registrada. 

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva maestra para un nuevo diseño. |

### Valor devuelto

Diapositiva añadida.

## Observaciones

1) El nuevo diseño se vinculará con el maestro definido en la presentación de destino. Por lo tanto, esto es análogo a copiar/pegar con la opción \"Use Destination Theme\" en PowerPoint. 2) El análogo de este método es el método [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) al que se accede mediante la propiedad [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)