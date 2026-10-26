---
title: get_Description()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací textový popis objektu Summary Zoom Section.
type: docs
weight: 27
url: /cs/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() metoda


Vrací textový popis objektu Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Poznámky


Příklad:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [SummaryZoomSection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)