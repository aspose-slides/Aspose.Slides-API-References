---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una copia de una diapositiva de diseño especificada al final de la colección.
type: docs
weight: 1
url: /es/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) método

Agrega una copia de una diapositiva de diseño especificada al final de la colección.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Added slide.

## Observaciones

1) La nueva diapositiva de diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es análoga a copiar/pegar con la opción \"Use Destination Theme\" en PowerPoint. 2) El análogo de este método es el método [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) al que se accede mediante la propiedad [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [MasterLayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)