---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina un diseño de la colección.
type: docs
weight: 27
url: /es/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) método

Elimina un diseño de la colección.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | La diapositiva de diseño que se elimina de la colección. |
## Observaciones

1) Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del diseño antes. 2) También puede usar el [ILayoutSlide::Remove](../../ilayoutslide/remove/) método para simplificar el código.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [ILayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)