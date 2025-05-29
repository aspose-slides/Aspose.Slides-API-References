---
title: OutputPath
second_title: Aspose.Slides für .NET API-Referenz
description: Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lese-/Schreib-String.
type: docs
weight: 60
url: /de/aspose.slides.export/ihtml5options/outputpath/
---

## IHtml5Options.OutputPath-Eigenschaft

Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lese-/Schreib-String.

```csharp
public string OutputPath { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-linked-images.html", SaveFormat.Html5, new Html5Options()
  {
      EmbedImages = false,
      OutputPath = "the_desired_path"
  });
}
```

### Siehe auch

* Schnittstelle [IHtml5Options](../../ihtml5options)
* Namespace [Aspose.Slides.Export](../../ihtml5options)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->