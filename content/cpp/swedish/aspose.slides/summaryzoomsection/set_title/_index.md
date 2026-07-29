---
title: set_Title()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar texttiteln för Summary Zoom Section-objektet.
type: docs
weight: 14
url: /sv/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) metod


Returnerar texttiteln för Summary Zoom [Section](../../section/)-objektet.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [SummaryZoomSection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)