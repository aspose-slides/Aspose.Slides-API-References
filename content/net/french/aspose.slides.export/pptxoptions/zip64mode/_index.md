---
title: Zip64Mode
second_title: Aspose.Sildes pour .NET Référence API
description: Spécifie si le format ZIP64 est utilisé pour le document de présentation. La valeur par défaut est IfNecessary
type: docs
weight: 40
url: /fr/aspose.slides.export/pptxoptions/zip64mode/
---

## PptxOptions.Zip64Mode propriété

Spécifie si le format ZIP64 est utilisé pour le document de présentation. La valeur par défaut est IfNecessary

```csharp
public Zip64Mode Zip64Mode { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("demo-zip64.pptx", SaveFormat.Pptx, new PptxOptions()
    {
        Zip64Mode = Zip64Mode.Always
    });
}
```

### Voir aussi

* enum [Zip64Mode](../../zip64mode)
* class [PptxOptions](../../pptxoptions)
* namespace [Aspose.Slides.Export](../../pptxoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->