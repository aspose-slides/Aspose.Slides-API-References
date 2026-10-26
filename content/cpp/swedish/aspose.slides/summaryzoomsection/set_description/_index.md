---
title: set_Description()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar textbeskrivningen av Summary Zoom Section-objektet.
type: docs
weight: 40
url: /sv/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) metod


Returnerar textbeskrivningen av Summary Zoom [Section](../../section/)-objektet.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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
* Klass [SummaryZoomSection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)