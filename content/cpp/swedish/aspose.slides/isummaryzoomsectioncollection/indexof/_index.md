---
title: IndexOf()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett index för det angivna SummaryZoomSection-objektet.
type: docs
weight: 53
url: /sv/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metod

Returnerar ett index för det angivna [SummaryZoomSection](../../summaryzoomsection/) objektet.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objekt för att hitta [ISummaryZoomSection](../../isummaryzoomsection/). |

### Returvärde

Index för ett [SummaryZoomSection](../../summaryzoomsection/) objekt eller -1 om [SummaryZoomSection](../../summaryzoomsection/) objektet inte är från denna samling.

## Anmärkningar

Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/) element med index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSection](../../isummaryzoomsection/)
* Klass [ISummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)