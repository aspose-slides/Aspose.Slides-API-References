---
title: Clear()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt alle SummaryZoomSection Objekte aus der Sammlung.
type: docs
weight: 105
url: /de/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() Methode


Entfernt alle [SummaryZoomSection](../../summaryzoomsection/) Objekte aus der Sammlung.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Hinweise


Das Beispiel zeigt, wie man das Summary Zoom [Section](../../section/) Element nach Index erhält: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Siehe auch

* Klasse [SummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)