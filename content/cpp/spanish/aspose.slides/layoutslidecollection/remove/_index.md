---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina un diseño de la colección.
type: docs
weight: 66
url: /es/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) método


Elimina un diseño de la colección.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | La diapositiva de diseño que se eliminará de la colección. |
## Observaciones



1) Para evitar que se lance la PptxEditException, compruebe antes la propiedad HasDependingSlides del diseño. 2) También puede usar el método [ILayoutSlide::Remove](../../ilayoutslide/remove/) para simplificar el código. 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ILayoutSlide](../../ilayoutslide/)
* Clase [LayoutSlideCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)