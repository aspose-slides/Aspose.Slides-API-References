---
title: Remove
second_title: Aspose.Slides für .NET API-Referenz
description: Entfernt ein Layout aus der Sammlung.
type: docs
weight: 30
url: /de/aspose.slides/ilayoutslidecollection/remove/
---

## ILayoutSlideCollection.Remove Methode

Entfernt ein Layout aus der Sammlung.

```csharp
public void Remove(ILayoutSlide value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | ILayoutSlide | Das Layoutfolien, das aus der Sammlung entfernt werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn das Layout in der Präsentation verwendet wird (seine Eigenschaft HasDependingSlides ist wahr). |

### Bemerkungen

1) Um das Auslösen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die [`Remove`](../../ilayoutslide/remove) Methode verwenden, um den Code zu vereinfachen.

### Siehe auch

* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Schnittstelle [ILayoutSlideCollection](../../ilayoutslidecollection)
* Namespace [Aspose.Slides](../../ilayoutslidecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->