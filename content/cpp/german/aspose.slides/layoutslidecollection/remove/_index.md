---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt ein Layout aus der Sammlung.
type: docs
weight: 66
url: /de/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) Methode

Entfernt ein Layout aus der Sammlung.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Das Layout-Slide, das aus der Sammlung entfernt werden soll. |

## Hinweise

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die Methode [ILayoutSlide::Remove](../../ilayoutslide/remove/) verwenden, um den Code zu vereinfachen. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [LayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)