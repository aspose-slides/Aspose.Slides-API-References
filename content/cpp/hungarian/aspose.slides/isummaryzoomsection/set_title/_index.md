---
title: set_Title()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a Summary Zoom Section objektum szöveges címét.
type: docs
weight: 14
url: /hu/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) metódus


Visszaadja a Summary Zoom [Section](../../section/) objektum szöveges címét.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## Megjegyzések


Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ISummaryZoomSection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)