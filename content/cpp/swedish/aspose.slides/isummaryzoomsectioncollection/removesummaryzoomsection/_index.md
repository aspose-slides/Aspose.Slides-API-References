---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides för C++ API-referens
description: Ta bort Summary Zoom Section-objektet från samlingen.
type: docs
weight: 40
url: /sv/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metod


Ta bort Summary Zoom [Section](../../section/) objekt från samlingen.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för vilken Summary Zoom [Section](../../section/) element ska tas bort [ISection](../../isection/). |
## Anmärkningar



Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/) elementet med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISection](../../isection/)
* Klass [ISummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)