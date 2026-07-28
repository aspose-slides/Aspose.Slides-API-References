---
title: get_Description()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a Summary Zoom Section objektum szöveges leírását.
type: docs
weight: 27
url: /hu/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() metódus

Visszaadja a Summary Zoom [Section](../../section/) objektum szöveges leírását.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
```

## Megjegyzések

Példa: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [SummaryZoomSection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)