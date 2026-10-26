---
title: get_Title()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací textový titulek objektu Summary Zoom Section.
type: docs
weight: 1
url: /cs/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() metoda


Vrací textový titulek objektu Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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