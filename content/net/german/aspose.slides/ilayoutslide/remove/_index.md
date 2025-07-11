---
title: Remove
second_title: Aspose.Sildes für .NET API-Referenz
description: Entfernt das Layout von der Präsentation.
type: docs
weight: 90
url: /de/aspose.slides/ilayoutslide/remove/
---

## ILayoutSlide.Remove-Methode

Entfernt das Layout von der Präsentation.

```csharp
public void Remove()
```

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn das Layout bereits von der Präsentation entfernt wurde oder wenn das Layout in der Präsentation verwendet wird (die HasDependingSlides-Eigenschaft ist true). |

### Hinweise

Um das Auslösen der PptxEditException zu vermeiden, überprüfen Sie vorher die HasDependingSlides-Eigenschaft des Layouts.

### Siehe auch

* Schnittstelle [ILayoutSlide](../../ilayoutslide)
* Namespace [Aspose.Slides](../../ilayoutslide)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->