---
title: set_Description()
second_title: Aspose.Slides per C++ API Reference
description: Restituisce la descrizione testuale dell'oggetto Summary Zoom Section.
type: docs
weight: 40
url: /it/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) metodo

Restituisce la descrizione testuale dell'oggetto Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## Note

Esempio:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ISummaryZoomSection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)