---
title: AnimateTransitions
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt die Animationsoption für Übergänge zurück oder legt sie fest. Lesen/SchreibenBoolean .
type: docs
weight: 30
url: /de/net/aspose.slides.export/html5options/animatetransitions/
---
## Html5Options.AnimateTransitions property

Gibt die Animationsoption für Übergänge zurück oder legt sie fest. Lesen/SchreibenBoolean .

```csharp
public bool AnimateTransitions { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateTransitions = true
  });
}
```

### Siehe auch

* class [Html5Options](../../html5options)
* namensraum [Aspose.Slides.Export](../../html5options)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->