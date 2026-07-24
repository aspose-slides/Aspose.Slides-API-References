---
title: Clear()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt alle SummaryZoomSection-Objekte aus der Sammlung.
type: docs
weight: 66
url: /de/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() Methode


Entfernt alle [SummaryZoomSection](../../summaryzoomsection/) Objekte aus der Sammlung.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Anmerkungen


Das Beispiel demonstriert das Abrufen des Summary Zoom [Section](../../section/) Elements über den Index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Siehe auch

* Klasse [ISummaryZoomSectionCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)