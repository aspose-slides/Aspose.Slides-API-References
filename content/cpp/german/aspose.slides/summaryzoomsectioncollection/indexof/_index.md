---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Index des angegebenen SummaryZoomSection-Objekts zurück.
type: docs
weight: 66
url: /de/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) Methode

Gibt den Index des angegebenen [SummaryZoomSection](../../summaryzoomsection/)-Objekts zurück.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/)-Objekt, um [ISummaryZoomSection](../../isummaryzoomsection/) zu finden. |

### Rückgabewert

Index eines [SummaryZoomSection](../../summaryzoomsection/)-Objekts oder -1, wenn das [SummaryZoomSection](../../summaryzoomsection/)-Objekt nicht aus dieser Sammlung stammt.

## Hinweise

Das Beispiel zeigt, wie man das Summary Zoom [Section](../../section/)-Element nach Index abruft:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [SummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)