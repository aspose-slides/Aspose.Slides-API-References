---
title: get_Title()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el título de texto del objeto Summary Zoom Section.
type: docs
weight: 1
url: /es/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() método

Devuelve el título de texto del objeto Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## Observaciones

Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ISummaryZoomSection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)