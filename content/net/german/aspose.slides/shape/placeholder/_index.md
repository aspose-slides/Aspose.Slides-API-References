---
title: Placeholder
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese-IPlaceholderaspnet.slides/iplaceholder.
type: docs
weight: 210
url: /de/aspose.slides/shape/placeholder/
---

## Shape.Placeholder-Eigenschaft

Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur-Lese- [`IPlaceholder`](../../iplaceholder).

```csharp
public IPlaceholder Placeholder { get; }
```

### Beispiele

Das folgende Beispiel zeigt, wie man den Text im Platzhalter ändert.

```csharp
[C#]
// Instanziiert eine Presentation-Klasse
using (Presentation pres = new Presentation("ReplacingText.pptx"))
{
    // Greift auf die erste Folie zu
    ISlide sld = pres.Slides[0];
    // Durchläuft die Formen, um den Platzhalter zu finden
    foreach (IShape shp in sld.Shapes)
        if (shp.Placeholder != null)
        {
            // Ändert den Text in jedem Platzhalter
            ((IAutoShape)shp).TextFrame.Text = "Das ist ein Platzhalter";
        }
    // Speichert die Präsentation auf der Festplatte
    pres.Save("output_out.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man den Eingabetext im Platzhalter festlegt.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation2.pptx"))
{
    ISlide slide = pres.Slides[0];
    foreach (IShape shape in slide.Slide.Shapes) // Durchläuft die Folie
    {
        if (shape.Placeholder != null && shape is AutoShape)
        {
            string text = "";
            if (shape.Placeholder.Type == PlaceholderType.CenteredTitle) // PowerPoint zeigt "Klicken Sie hier, um Titel hinzuzufügen" an
            {
                text = "Titel hinzufügen";
            }
            else if (shape.Placeholder.Type == PlaceholderType.Subtitle) // Fügt Untertitel hinzu
            {
                text = "Untertitel hinzufügen";
            }
            ((IAutoShape)shape).TextFrame.Text = text;
            Console.WriteLine($"Platzhalter mit Text: {text}");
        }
    }
    pres.Save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IPlaceholder](../../iplaceholder)
* Klasse [Shape](../../shape)
* Namespace [Aspose.Slides](../../shape)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->