---
title: Remove
second_title: Aspose.Slides für .NET-API-Referenz
description: Entfernt das Layout aus der Präsentation.
type: docs
weight: 80
url: /de/aspose.slides/layoutslide/remove/
---
## LayoutSlide.Remove method

Entfernt das Layout aus der Präsentation.

```csharp
public void Remove()
```

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wird ausgelöst, wenn das Layout bereits aus der Präsentation entfernt wurde oder wenn das Layout in der Präsentation verwendet wird (seine Eigenschaft HasDependingSlides ist wahr). |

### Bemerkungen

Um das Auslösen der PptxEditException zu vermeiden, überprüfen Sie vorher die HasDependingSlides-Eigenschaft des Layouts.

### Siehe auch

* class [LayoutSlide](../../layoutslide)
* namensraum [Aspose.Slides](../../layoutslide)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
