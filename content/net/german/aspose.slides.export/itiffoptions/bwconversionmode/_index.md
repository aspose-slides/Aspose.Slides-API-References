---
title: BwConversionMode
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt den Algorithmus zum Konvertieren eines Farbbildes in ein schwarz-weiß Bild an. Diese Option wird nur angewendet, wenn CompressionType aspose.slides.export/itiffoptions/compressiontype auf CCITT4 oder CCITT3 gesetzt ist. Lesen/Schreiben von BlackWhiteConversionMode aspose.slides.export/blackwhiteconversionmode. Standard ist Default.
type: docs
weight: 20
url: /de/aspose.slides.export/itiffoptions/bwconversionmode/
---

## ITiffOptions.BwConversionMode-Eigenschaft

Gibt den Algorithmus zum Konvertieren eines Farbbildes in ein schwarz-weiß Bild an. Diese Option wird nur angewendet, wenn [`CompressionType`](../compressiontype) auf CCITT4 oder CCITT3 gesetzt ist. Lesen/Schreiben von [`BlackWhiteConversionMode`](../../blackwhiteconversionmode). Standard ist Default.

```csharp
public BlackWhiteConversionMode BwConversionMode { get; set; }
```

### Beispiele

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

### Siehe auch

* enum [BlackWhiteConversionMode](../../blackwhiteconversionmode)
* interface [ITiffOptions](../../itiffoptions)
* namespace [Aspose.Slides.Export](../../itiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->