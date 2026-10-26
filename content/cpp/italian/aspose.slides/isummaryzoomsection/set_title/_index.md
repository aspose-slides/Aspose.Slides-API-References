---
title: set_Title()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il titolo di testo dell'oggetto Summary Zoom Section.
type: docs
weight: 14
url: /it/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) metodo

Restituisce il titolo di testo dell'oggetto Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## Osservazioni


Esempio:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ISummaryZoomSection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)