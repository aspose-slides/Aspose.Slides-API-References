---
title: SlidesLayoutOptions
second_title: Aspose.Slides für .NET API Referenz
description: Ruft den Modus ab oder setzt ihn, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 70
url: /de/aspose.slides.export/ihtml5options/slideslayoutoptions/
---

## IHtml5Options.SlidesLayoutOptions-Eigenschaft

Ruht den Modus ab oder setzt ihn, in dem Folien auf der Seite platziert werden, wenn eine Präsentation [`ISlidesLayoutOptions`](../../islideslayoutoptions) exportiert wird.

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Html5Options options = new Html5Options
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.html", SaveFormat.Html5, options);
}
```

### Siehe Auch

* Schnittstelle [ISlidesLayoutOptions](../../islideslayoutoptions)
* Schnittstelle [IHtml5Options](../../ihtml5options)
* Namensraum [Aspose.Slides.Export](../../ihtml5options)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->