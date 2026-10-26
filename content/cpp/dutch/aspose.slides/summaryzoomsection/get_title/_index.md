---
title: get_Title()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de teksttitel van het Summary Zoom Section object.
type: docs
weight: 1
url: /nl/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() methode


Retourneert de teksttitel van de Summary Zoom [Section](../../section/) object.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [SummaryZoomSection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)