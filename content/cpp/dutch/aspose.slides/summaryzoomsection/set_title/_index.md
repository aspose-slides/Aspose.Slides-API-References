---
title: set_Title()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de teksttitel van het Summary Zoom Section object.
type: docs
weight: 14
url: /nl/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) methode

Retourneert de teksttitel van het Summary Zoom [Section](../../section/) object.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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