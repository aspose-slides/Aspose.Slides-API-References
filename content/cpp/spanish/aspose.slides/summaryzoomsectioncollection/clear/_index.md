---
title: Clear()
second_title: Referencia API de Aspose.Slides para C++
description: Elimina todos los objetos SummaryZoomSection de la colección.
type: docs
weight: 105
url: /es/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() método


Elimina todos los objetos [SummaryZoomSection](../../summaryzoomsection/) de la colección.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Observaciones


El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Ver también

* Clase [SummaryZoomSectionCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)