---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhält ISummaryZoomSectionCollection für das Summary Zoom Frame-Objekt.
type: docs
weight: 14
url: /de/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() Methode

Erhält [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) für das Summary Zoom Frame-Objekt.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Hinweise

Das Beispiel zeigt das Abrufen des Summary Zoom [Section](../../section/) Elements nach Index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasse [SummaryZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)