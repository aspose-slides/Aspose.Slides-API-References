---
title: PrintSlideNumbers
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt an, ob die angezeigten Foliennummern gedruckt werden sollen oder nicht.
type: docs
weight: 50
url: /de/aspose.slides.export/handoutlayoutingoptions/printslidenumbers/
---

## HandoutLayoutingOptions.PrintSlideNumbers-Eigenschaft

Gibt an, ob die angezeigten Foliennummern gedruckt werden sollen oder nicht.

```csharp
public bool PrintSlideNumbers { get; set; }
```

### Anmerkungen

Der Standardwert ist **true**.

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
            PrintSlideNumbers = false
        }
    };
    
    pres.Slides[0].GetThumbnail(options, new Size(1920, 1080)).Save("pres-handout.png");
}
```

### Siehe auch

* Klasse [HandoutLayoutingOptions](../../handoutlayoutingoptions)
* Namensraum [Aspose.Slides.Export](../../handoutlayoutingoptions)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->