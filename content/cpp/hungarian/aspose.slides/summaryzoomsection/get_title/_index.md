---
title: get_Title()
second_title: Aspose.Slides C++ API Referenciája
description: Visszaadja a Summary Zoom Section objektum szöveges címét.
type: docs
weight: 1
url: /hu/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() metódus

Visszaadja a Summary Zoom [Section](../../section/) objektum szöveges címét.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* Osztály [SummaryZoomSection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)