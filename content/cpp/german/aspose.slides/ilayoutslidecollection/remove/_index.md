---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt ein Layout aus der Sammlung.
type: docs
weight: 27
url: /de/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) Methode

Entfernt ein Layout aus der Sammlung.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Die Layout-Folie, die aus der Sammlung entfernt werden soll. |
## Anmerkungen

1) Um das Werfen von PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die [ILayoutSlide::Remove](../../ilayoutslide/remove/) Methode verwenden, um den Code zu vereinfachen. 
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [ILayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)