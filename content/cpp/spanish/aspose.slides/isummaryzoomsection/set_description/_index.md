---
title: set_Description()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la descripción de texto del objeto Summary Zoom Section.
type: docs
weight: 40
url: /es/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) método


Devuelve la descripción de texto del objeto Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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
* Clase [ISummaryZoomSection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)