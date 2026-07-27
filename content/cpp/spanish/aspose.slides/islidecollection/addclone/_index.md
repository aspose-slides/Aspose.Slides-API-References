---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade una copia de una diapositiva especificada al final de la colección.
type: docs
weight: 14
url: /es/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) método


Añade una copia de una diapositiva especificada al final de la colección.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Nueva diapositiva.
## Observaciones



Al clonar una diapositiva entre diferentes presentaciones, el maestro de la diapositiva también puede clonarse. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples copias del mismo maestro de diapositiva. La clonación manual de maestros de diapositiva no será ni prevenida ni registrada. Si necesita más control sobre el proceso de clonación, utilice [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) o [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) para clonar diapositivas, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) o [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) para clonar diseños y [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar maestros. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) método


Añade una copia de una diapositiva especificada al final de la sección especificada.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) para una nueva diapositiva. |

### Valor devuelto

Nueva diapositiva.
## Observaciones



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Ahora la segunda sección contiene una copia de la primera diapositiva.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) método


Añade una copia de una diapositiva especificada al final de la colección.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositiva de diseño para una nueva diapositiva. |

### Valor devuelto

Nueva diapositiva.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) método


Añade una copia de una diapositiva origen especificada al final de la colección. El diseño apropiado se seleccionará automáticamente del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva origen). Si no hay un diseño apropiado, entonces el diseño de la diapositiva origen se clonará (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva maestra para una nueva diapositiva. |
| allowCloneMissingLayout | **bool** | Si no hay un diseño apropiado en el maestro especificado, entonces el diseño de la diapositiva origen se clonará (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

### Valor devuelto

Nueva diapositiva.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [ISlideCollection](../)
* Clase [ISection](../../isection/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IMasterSlide](../../imasterslide/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)