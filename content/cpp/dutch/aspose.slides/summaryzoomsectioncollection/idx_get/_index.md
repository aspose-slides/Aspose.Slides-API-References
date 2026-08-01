---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het element op op de opgegeven index. Alleen-lezen ISummaryZoomSection.
type: docs
weight: 40
url: /nl/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) methode


Haalt het element op op de opgegeven index. Alleen-lezen [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Opmerkingen


Het voorbeeld laat zien hoe een Summary Zoom [Section](../../section/) element wordt opgehaald op index: 
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
* Klasse [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)