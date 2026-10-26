---
title: Clear()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort alla SummaryZoomSection-objekt från samlingen.
type: docs
weight: 66
url: /sv/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() metod

Tar bort alla [SummaryZoomSection](../../summaryzoomsection/) objekt från samlingen.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Anmärkningar

Exemplet visar hur man hämtar Summary Zoom [Section](../../section/) element via index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Se även

* Klass [ISummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)