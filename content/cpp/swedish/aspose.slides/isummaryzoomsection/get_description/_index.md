---
title: get_Description()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar textbeskrivningen av Summary Zoom Section-objektet.
type: docs
weight: 27
url: /sv/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() method

Returnerar textbeskrivningen av Summary Zoom [Section](../../section/)-objektet.

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
```

## Anmärkningar

Exempel:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ISummaryZoomSection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)