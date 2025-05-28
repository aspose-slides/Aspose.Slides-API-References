---
title: EmbedImages
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt die Option zum Einbetten von Bildern zurück oder setzt sie. Lese-/Schreib-Boolean.
type: docs
weight: 50
url: /de/aspose.slides.export/html5options/embedimages/
---

## Html5Options.EmbedImages-Eigenschaft

Gibt die Option zum Einbetten von Bildern zurück oder setzt sie. Lese-/Schreib-Boolean.

```csharp
public bool EmbedImages { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-linked-images.html", SaveFormat.Html5, new Html5Options()
  {
      EmbedImages = false
  });
}
```

### Siehe auch

* Klasse [Html5Options](../../html5options)
* Namespace [Aspose.Slides.Export](../../html5options)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->