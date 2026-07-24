---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft das Element am angegebenen Index ab. Nur lesbar ISummaryZoomSection.
type: docs
weight: 40
url: /de/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) Methode

Ruft das Element am angegebenen Index ab. Nur lesbar [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Anmerkungen

Das Beispiel demonstriert das Abrufen des Summary Zoom [Section](../../section/) Elements per Index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasse [SummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)