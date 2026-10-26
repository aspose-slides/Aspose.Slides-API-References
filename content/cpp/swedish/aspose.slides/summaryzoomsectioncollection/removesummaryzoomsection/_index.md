---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides för C++ API-referens
description: Ta bort Summary Zoom Section-objektet från samlingen.
type: docs
weight: 79
url: /sv/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metod

Ta bort Summary Zoom [Section](../../section/) objekt från samlingen.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för vilken Summary Zoom [Section](../../section/) elementet ska tas bort [ISection](../../isection/). |
## Anmärkningar



Exemplet demonstrerar att hämta Summary Zoom [Section](../../section/) elementet med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISection](../../isection/)
* Klass [SummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)