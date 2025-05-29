---
title: BwConversionMode
second_title: Aspose.Slides pour la référence API .NET
description: Spécifie l'algorithme pour convertir une image couleur en une image en noir et blanc. Cette option ne sera appliquée que si CompressionType aspose.slides.export/itiffoptions/compressiontype est défini sur CCITT4 ou CCITT3 Lire/écrire BlackWhiteConversionMode aspose.slides.export/blackwhiteconversionmode. La valeur par défaut est Default.
type: docs
weight: 20
url: /fr/aspose.slides.export/itiffoptions/bwconversionmode/
---

## Propriété ITiffOptions.BwConversionMode

Spécifie l'algorithme pour convertir une image couleur en une image en noir et blanc. Cette option ne sera appliquée que si [`CompressionType`](../compressiontype) est défini sur CCITT4 ou CCITT3 Lire/écrire [`BlackWhiteConversionMode`](../../blackwhiteconversionmode). La valeur par défaut est Default.

```csharp
public BlackWhiteConversionMode BwConversionMode { get; set; }
```

### Exemples

```csharp
[C#]
TiffOptions tiffOptions = new TiffOptions();
tiffOptions.CompressionType = TiffCompressionTypes.CCITT4;
tiffOptions.BwConversionMode = BlackWhiteConversionMode.Dithering;

using (var presentation = new Presentation())
{
    presentation.Save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
}
```

### Voir aussi

* enum [BlackWhiteConversionMode](../../blackwhiteconversionmode)
* interface [ITiffOptions](../../itiffoptions)
* namespace [Aspose.Slides.Export](../../itiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->