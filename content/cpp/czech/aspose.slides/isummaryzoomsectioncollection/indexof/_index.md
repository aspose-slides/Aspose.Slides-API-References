---
title: IndexOf()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací index zadaného objektu SummaryZoomSection.
type: docs
weight: 53
url: /cs/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metoda

Vrací index určeného [SummaryZoomSection](../../summaryzoomsection/) objektu.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objekt k nalezení [ISummaryZoomSection](../../isummaryzoomsection/). |

### Návratová hodnota

Index objektu [SummaryZoomSection](../../summaryzoomsection/) nebo -1, pokud objekt [SummaryZoomSection](../../summaryzoomsection/) není z této kolekce.

## Poznámky

Příklad ukazuje získání prvku Summary Zoom [Section](../../section/) podle indexu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [ISummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)