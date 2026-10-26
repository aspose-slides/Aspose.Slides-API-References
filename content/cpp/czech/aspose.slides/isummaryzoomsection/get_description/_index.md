---
title: get_Description()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací textový popis objektu Summary Zoom Section.
type: docs
weight: 27
url: /cs/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() metoda

Vrací textový popis objektu Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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
* Třída [ISummaryZoomSection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)