---
title: get_SummaryZoomCollection()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene ISummaryZoomSectionCollection para el objeto Summary Zoom Frame.
type: docs
weight: 14
url: /es/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() método


Obtiene [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) para el objeto Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Observaciones


El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Clase [SummaryZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)