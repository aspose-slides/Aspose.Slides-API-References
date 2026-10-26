---
title: GetSummarySection()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar Summary Zoom Section-element för den angivna sektionen.
type: docs
weight: 92
url: /sv/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metod

Returnerar Summary Zoom [Section](../../section/) element för den angivna sektionen.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för att hitta [ISection](../../isection/) |

### Returvärde

[ISummaryZoomSection](../../isummaryzoomsection/) eller null om samlingen inte innehåller element för sektionen.

## Anmärkningar

Exemplet visar hur man hämtar Summary Zoom [Section](../../section/) element efter index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSection](../../isummaryzoomsection/)
* Klass [ISection](../../isection/)
* Klass [SummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)