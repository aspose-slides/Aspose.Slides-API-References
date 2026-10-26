---
title: GetSummarySection()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar Summary Zoom Section-elementet för den givna sektionen.
type: docs
weight: 27
url: /sv/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metod

Returns Summary Zoom [Section](../../section/) element for the given section.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för att hitta [ISection](../../isection/) |

### Returvärde

[ISummaryZoomSection](../../isummaryzoomsection/) eller null om samlingen inte innehåller element för sektionen.

## Anmärkningar

The example demonstrates getting Summary Zoom [Section](../../section/) element by index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSection](../../isummaryzoomsection/)
* Klass [ISection](../../isection/)
* Klass [ISummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)