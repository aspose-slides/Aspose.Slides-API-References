---
title: AddSummaryZoomSection()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Summary Zoom Section-objekt och lägger till det i samlingen
type: docs
weight: 14
url: /sv/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metod


Skapar ett nytt Summary Zoom [Section](../../section/) objekt och lägger till det i samlingen

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för ett nytt Summary Zoom [Section](../../section/) element [ISection](../../isection/) |

### Returvärde

Tillagt [ISummaryZoomFrame](../../isummaryzoomframe/) element
## Anmärkningar



Om ett element för detta avsnitt redan finns i samlingen, returneras det befintliga elementet. 

Exemplet demonstrerar hur man hämtar Summary Zoom [Section](../../section/) element med index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSection](../../isummaryzoomsection/)
* Klass [ISection](../../isection/)
* Klass [ISummaryZoomSectionCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)