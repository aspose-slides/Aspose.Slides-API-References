---
title: get_Title()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il titolo testuale dell'oggetto Summary Zoom Section.
type: docs
weight: 1
url: /it/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() metodo


Restituisce il titolo testuale dell'oggetto Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* Classe [SummaryZoomSection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)