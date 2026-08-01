---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het element op op de opgegeven index. Alleen-lezen ISummaryZoomSection.
type: docs
weight: 1
url: /nl/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) method


Haalt het element op bij de opgegeven index. Alleen-lezen [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Opmerkingen


Het voorbeeld laat zien hoe een Summary Zoom [Section](../../section/) element op te halen op basis van index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [ISummaryZoomSectionCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)