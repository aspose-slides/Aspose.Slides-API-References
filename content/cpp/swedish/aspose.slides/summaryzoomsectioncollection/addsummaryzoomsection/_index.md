---
title: AddSummaryZoomSection()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Summary Zoom Section-objekt och lägger till det i samlingen
type: docs
weight: 53
url: /sv/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metod

Skapar ett nytt Summary Zoom [Section](../../section/)-objekt och lägger till det i samlingen

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för ett nytt Summary Zoom [Section](../../section/)-element [ISection](../../isection/) |

## Returvärde

Tillagt [ISummaryZoomFrame](../../isummaryzoomframe/) element

## Anmärkningar

Om ett element för detta avsnitt redan finns i samlingen, returneras det befintliga elementet.

Exemplet visar hur man får Summary Zoom [Section](../../section/)-element efter index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSection](../../isummaryzoomsection/)
* Klass [ISection](../../isection/)
* Klass [SummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)