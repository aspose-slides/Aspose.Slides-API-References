---
title: set_Title()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací textový název objektu Summary Zoom Section.
type: docs
weight: 14
url: /cs/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) metoda

Vrací textový titulek objektu Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## Poznámky

Příklad:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [SummaryZoomSection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)