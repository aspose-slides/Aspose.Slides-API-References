---
title: Clear()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a gyűjteményből az összes SummaryZoomSection objektumot.
type: docs
weight: 66
url: /hu/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() módszer


Eltávolítja az összes [SummaryZoomSection](../../summaryzoomsection/) objektumot a gyűjteményből.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Megjegyzés


A példa bemutatja, hogyan lehet index alapján lekérni a Summary Zoom [Section](../../section/) elemet: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Lásd még

* Osztály [ISummaryZoomSectionCollection](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)