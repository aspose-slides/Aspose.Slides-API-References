---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una copia de una diapositiva de diseño especificada a la presentación.
type: docs
weight: 1
url: /es/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) método

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva añadida.

## Observaciones

Al clonar un diseño entre diferentes presentaciones, el maestro del diseño también puede clonarse para mantener el formato original. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de diapositivas maestras no será ni evitada ni registrada.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) método

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva maestra para un nuevo diseño. |

### Valor devuelto

Diapositiva añadida.

## Observaciones

El nuevo diseño se vinculará con el maestro definido en la presentación de destino. Por lo tanto, esto es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IGlobalLayoutSlideCollection](../)
* Clase [IMasterSlide](../../imasterslide/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)