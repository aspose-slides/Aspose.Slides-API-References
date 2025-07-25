---
title: SlidesLayoutOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation auf der Seite platziert werden ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 180
url: /de/aspose.slides.export/pdfoptions/slideslayoutoptions/
---

## PdfOptions.SlidesLayoutOptions-Eigenschaft

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [`ISlidesLayoutOptions`](../../islideslayoutoptions) auf der Seite platziert werden.

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions options = new PdfOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.pdf", SaveFormat.Pdf, options);
}
```

### Siehe auch

* Schnittstelle [ISlidesLayoutOptions](../../islideslayoutoptions)
* Klasse [PdfOptions](../../pdfoptions)
* Namespace [Aspose.Slides.Export](../../pdfoptions)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->