---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el elemento en el índice especificado. Solo lectura ISummaryZoomSection.
type: docs
weight: 40
url: /es/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) método


Obtiene el elemento en el índice especificado. Solo lectura [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Observaciones


El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
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
* Clase [SummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)