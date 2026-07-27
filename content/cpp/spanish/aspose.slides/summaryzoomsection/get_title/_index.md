---
title: get_Title()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el título de texto del objeto Summary Zoom Section.
type: docs
weight: 1
url: /es/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() método

Returns the text title of the Summary Zoom [Section](../../section/) object.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## Observaciones

Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [SummaryZoomSection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)