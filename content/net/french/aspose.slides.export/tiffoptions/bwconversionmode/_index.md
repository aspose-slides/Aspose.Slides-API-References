---
title: BwConversionMode
second_title: Aspose.Slides pour .NET API Reference
description: Spécifie l'algorithme pour convertir une image couleur en une image noir et blanc. Cette option ne sera appliquée que si CompressionTypeaspose.slides.export/tiffoptions/compressiontype est définie sur CCITT4 ou CCITT3 Lire/écrire BlackWhiteConversionModeaspose.slides.export/blackwhiteconversionmode. Par défaut, c'est Default.
type: docs
weight: 20
url: /fr/aspose.slides.export/tiffoptions/bwconversionmode/
---

## Propriété TiffOptions.BwConversionMode

Spécifie l'algorithme pour convertir une image couleur en une image noir et blanc. Cette option ne sera appliquée que si [`CompressionType`](../compressiontype) est définie sur CCITT4 ou CCITT3 Lire/écrire [`BlackWhiteConversionMode`](../../blackwhiteconversionmode). Par défaut, c'est Default.

```csharp
public BlackWhiteConversionMode BwConversionMode { get; set; }
```

### Exemples

```csharp
[C#]
TiffOptions tiffOptions = new TiffOptions();
tiffOptions.CompressionType = TiffCompressionTypes.CCITT4
tiffOptions.BwConversionMode = BlackWhiteConversionMode.Dithering;

using (var presentation = new Presentation())
{
    presentation.Save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
}
```

```csharp
[Visual Basic]
Dim tiffOptions As New TiffOptions()
tiffOptions.CompressionType = TiffCompressionTypes.CCITT4
tiffOptions.BwConversionMode = BlackWhiteConversionMode.Dithering

Using presentation As New Presentation()
    presentation.Save(tiffFilePath, SaveFormat.Tiff, tiffOptions)
End Using
```

### Voir aussi

* enum [BlackWhiteConversionMode](../../blackwhiteconversionmode)
* class [TiffOptions](../../tiffoptions)
* namespace [Aspose.Slides.Export](../../tiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->