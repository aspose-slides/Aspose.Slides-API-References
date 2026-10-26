---
title: IndexOf()
second_title: Aspose.Slides pro C++ – API reference
description: Vrací index zadaného objektu SummaryZoomSection.
type: docs
weight: 66
url: /cs/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metoda

Vrátí index určeného objektu [SummaryZoomSection](../../summaryzoomsection/).

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objekt k nalezení [ISummaryZoomSection](../../isummaryzoomsection/). |

### Návratová hodnota

Index objektu [SummaryZoomSection](../../summaryzoomsection/) nebo -1, pokud objekt [SummaryZoomSection](../../summaryzoomsection/) není z této kolekce.

## Poznámky

Příklad ukazuje získání Summary Zoom [Section](../../section/) prvku pomocí indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```


## Další informace

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [SummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)