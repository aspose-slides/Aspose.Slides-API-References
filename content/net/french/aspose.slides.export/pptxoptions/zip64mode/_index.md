---
title: Zip64Mode
second_title: Aspose.Slides pour .NET Référence API
description: Spécifie si le format ZIP64 est utilisé pour le document de présentation. La valeur par défaut est IfNecessary
type: docs
weight: 40
url: /fr/aspose.slides.export/pptxoptions/zip64mode/
---

## Propriété PptxOptions.Zip64Mode

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

### Voir Aussi

* enum [Zip64Mode](../../zip64mode)
* class [PptxOptions](../../pptxoptions)
* namespace [Aspose.Slides.Export](../../pptxoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->