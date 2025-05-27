---
title: BwConversionMode
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el algoritmo para convertir una imagen en color en una imagen en blanco y negro. Esta opción se aplicará solo si CompressionTypeaspose.slides.export/itiffoptions/compressiontype está configurado en CCITT4 o CCITT3 Leer/escribir BlackWhiteConversionModeaspose.slides.export/blackwhiteconversionmode. Por defecto es Default.
type: docs
weight: 20
url: /es/aspose.slides.export/itiffoptions/bwconversionmode/
---

## Propiedad ITiffOptions.BwConversionMode

Especifica el algoritmo para convertir una imagen en color en una imagen en blanco y negro. Esta opción se aplicará solo si [`CompressionType`](../compressiontype) está configurado en CCITT4 o CCITT3 Leer/escribir [`BlackWhiteConversionMode`](../../blackwhiteconversionmode). Por defecto es Default.

```csharp
public BlackWhiteConversionMode BwConversionMode { get; set; }
```

### Ejemplos

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

### Ver También

* enum [BlackWhiteConversionMode](../../blackwhiteconversionmode)
* interface [ITiffOptions](../../itiffoptions)
* namespace [Aspose.Slides.Export](../../itiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->