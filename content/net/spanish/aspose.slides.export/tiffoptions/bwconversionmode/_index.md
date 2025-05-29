---
title: BwConversionMode
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción solo se aplicará si CompressionTypeaspose.slides.export/tiffoptions/compressiontype está configurada en CCITT4 o CCITT3. Leer/escribir BlackWhiteConversionModeaspose.slides.export/blackwhiteconversionmode. El valor predeterminado es Default.
type: docs
weight: 20
url: /es/aspose.slides.export/tiffoptions/bwconversionmode/
---

## Propiedad TiffOptions.BwConversionMode

Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción solo se aplicará si [`CompressionType`](../compressiontype) está configurada en CCITT4 o CCITT3. Leer/escribir [`BlackWhiteConversionMode`](../../blackwhiteconversionmode). El valor predeterminado es Default.

```csharp
public BlackWhiteConversionMode BwConversionMode { get; set; }
```

### Ejemplos

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

### Vea También

* enum [BlackWhiteConversionMode](../../blackwhiteconversionmode)
* class [TiffOptions](../../tiffoptions)
* namespace [Aspose.Slides.Export](../../tiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->