---
title: Clear()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja az összes SummaryZoomSection objektumot a gyűjteményből.
type: docs
weight: 105
url: /hu/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() metódus


Eltávolít minden [SummaryZoomSection](../../summaryzoomsection/) objektumot a gyűjteményből.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Megjegyzések


A példa bemutatja, hogyan lehet a Summary Zoom [Section](../../section/) elemet index alapján lekérni: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Lásd még

* Osztály [SummaryZoomSectionCollection](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)