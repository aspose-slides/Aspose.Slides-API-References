---
title: AddTablePlaceholder
second_title: Aspose.Slides für .NET API Referenz
description: Fügt eine neue Platzhalterform zur Layout-Folie hinzu, um eine Tabelle zu halten.
type: docs
weight: 70
url: /de/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---

## ILayoutPlaceholderManager.AddTablePlaceholder Methode

Fügt eine neue Platzhalterform zur Layout-Folie hinzu, um eine Tabelle zu halten.

```csharp
public IAutoShape AddTablePlaceholder(float x, float y, float width, float height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | Die X-Koordinate der neuen Platzhalterform. |
| y | Single | Die Y-Koordinate der neuen Platzhalterform. |
| width | Single | Die Breite der neuen Platzhalterform. |
| height | Single | Die Höhe der neuen Platzhalterform. |

### Rückgabewert

Erstellt [`IAutoShape`](../../iautoshape) mit einem Tabellenplatzhalter.

### Beispiele

Das folgende Beispiel zeigt, wie man die Tabellenplatzhalterform zur Layout-Folie hinzufügt.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddTablePlaceholder(20, 20, 500, 200);
}
```

### Siehe auch

* Schnittstelle [IAutoShape](../../iautoshape)
* Schnittstelle [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* Namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->