---
title: RefreshThumbnail
second_title: Aspose.Sildes für .NET API Referenz
description: Gibt an, ob das Präsentationsminiaturbild aktualisiert wird. Lese-/Schreib-Booleans. Der Standardwert ist true.
type: docs
weight: 30
url: /de/aspose.slides.export/pptxoptions/refreshthumbnail/
---

## PptxOptions.RefreshThumbnail-Eigenschaft

Gibt an, ob das Präsentationsminiaturbild aktualisiert wird. Lese-/Schreib-Booleans. Der Standardwert ist **true**.

```csharp
public bool RefreshThumbnail { get; set; }
```

### Bemerkungen

Wenn der Optionswert **true** ist, wird das neue Miniaturbild generiert.

Wenn der Optionswert **false** ist, wird das aktuelle Miniaturbild unverändert gespeichert.

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, new PptxOptions()
    {
        RefreshThumbnail = false
    });
}
```

### Siehe auch

* Klasse [PptxOptions](../../pptxoptions)
* Namespace [Aspose.Slides.Export](../../pptxoptions)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->