---
title: AnimateShapes
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt die Animationsoption für Formen zurück oder legt sie fest. Lesen/SchreibenBoolean .
type: docs
weight: 10
url: /de/aspose.slides.export/ihtml5options/animateshapes/
---
## IHtml5Options.AnimateShapes property

Gibt die Animationsoption für Formen zurück oder legt sie fest. Lesen/SchreibenBoolean .

```csharp
public bool AnimateShapes { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true
  });
}
```

### Siehe auch

* interface [IHtml5Options](../../ihtml5options)
* namensraum [Aspose.Slides.Export](../../ihtml5options)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
