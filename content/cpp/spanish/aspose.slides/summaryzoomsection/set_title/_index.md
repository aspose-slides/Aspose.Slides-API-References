---
title: set_Title()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el título de texto del objeto Summary Zoom Section.
type: docs
weight: 14
url: /es/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) método


Devuelve el título de texto del objeto Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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
* Clase [SummaryZoomSection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)