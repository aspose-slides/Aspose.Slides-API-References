---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett index för det angivna SummaryZoomSection-objektet.
type: docs
weight: 66
url: /sv/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metod


Returns an index of the specified [SummaryZoomSection](../../summaryzoomsection/) object.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objekt att hitta [ISummaryZoomSection](../../isummaryzoomsection/). |

### Returnvärde

Index för ett [SummaryZoomSection](../../summaryzoomsection/)-objekt eller -1 om [SummaryZoomSection](../../summaryzoomsection/)-objektet inte kommer från den här samlingen.
## Anmärkningar



Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/)-elementet med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)