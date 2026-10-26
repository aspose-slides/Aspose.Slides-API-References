---
title: get_Description()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la descripción de texto del objeto Summary Zoom Section.
type: docs
weight: 27
url: /es/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() método


Devuelve la descripción de texto del objeto Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Observaciones


Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [SummaryZoomSection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)