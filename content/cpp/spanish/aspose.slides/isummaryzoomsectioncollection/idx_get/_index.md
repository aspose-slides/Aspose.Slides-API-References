---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el elemento en el índice especificado. Sólo lectura ISummaryZoomSection.
type: docs
weight: 1
url: /es/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) método


Obtiene el elemento en el índice especificado. Sólo lectura [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Observaciones


El ejemplo demuestra obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomSection](../../isummaryzoomsection/)
* Clase [ISummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)