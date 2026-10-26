---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ISummaryZoomSectionCollection für das Summary Zoom Frame-Objekt ab.
type: docs
weight: 14
url: /de/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() Methode


Erhält [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) für das Summary Zoom Frame-Objekt.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Bemerkungen


Das Beispiel zeigt, wie das Summary Zoom [Section](../../section/)-Element per Index abgerufen wird: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasse [ISummaryZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)