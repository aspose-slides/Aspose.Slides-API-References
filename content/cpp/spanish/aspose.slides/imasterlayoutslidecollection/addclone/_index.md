---
title: AddClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una copia de una diapositiva de diseño especificada al final de la colección.
type: docs
weight: 1
url: /es/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) método

Agrega una copia de una diapositiva de diseño especificada al final de la colección.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor devuelto

Diapositiva añadida.

## Comentarios

1) El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es el análogo de copiar/pegar con la opción \"Use Destination Theme\" en PowerPoint. 2) El análogo de este método es el método [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) al que se accede mediante la propiedad [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [IMasterLayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)