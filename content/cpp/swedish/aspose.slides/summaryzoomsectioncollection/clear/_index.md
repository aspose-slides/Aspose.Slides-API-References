---
title: Clear()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla SummaryZoomSection-objekt från samlingen.
type: docs
weight: 105
url: /sv/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() metod

Tar bort alla [SummaryZoomSection](../../summaryzoomsection/) objekt från samlingen.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Anmärkningar

Exemplet demonstrerar att hämta Summary Zoom [Section](../../section/) element efter index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Se också

* Klass [SummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)