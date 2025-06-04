---
title: AddOnlineImagePlaceholder
second_title: Aspose.Slides für .NET API Referenz
description: Fügt eine neue Platzhalterform zur Layout-Folie hinzu, um ein Online-Bild zu halten.
type: docs
weight: 40
url: /de/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---

## LayoutPlaceholderManager.AddOnlineImagePlaceholder Methode

Fügt eine neue Platzhalterform zur Layout-Folie hinzu, um ein Online-Bild zu halten.

```csharp
public IAutoShape AddOnlineImagePlaceholder(float x, float y, float width, float height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | Die X-Koordinate der neuen Platzhalterform. |
| y | Single | Die Y-Koordinate der neuen Platzhalterform. |
| width | Single | Die Breite der neuen Platzhalterform. |
| height | Single | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [`IAutoShape`](../../iautoshape) mit einem Online-Bild-Platzhalter.

### Beispiele

Das folgende Beispiel zeigt, wie man die Online-Bild-Platzhalterform zur Layout-Folie hinzufügt.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddOnlineImagePlaceholder(20, 20, 200, 200);
}
```

### Siehe auch

* interface [IAutoShape](../../iautoshape)
* class [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* namespace [Aspose.Slides](../../layoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->