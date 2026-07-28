---
title: set_Description()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a Summary Zoom Section objektum szöveges leírását.
type: docs
weight: 40
url: /hu/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) metódus

Visszaadja a Summary Zoom [Section](../../section/) objektum szöveges leírását.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
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