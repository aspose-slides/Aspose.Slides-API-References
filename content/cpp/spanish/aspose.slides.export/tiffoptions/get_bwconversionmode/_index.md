---
title: get_BwConversionMode()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si ITiffOptions::get_CompressionType() está configurado a TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3 Lea BlackWhiteConversionMode. El valor predeterminado es BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /es/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() método

Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) está configurado a [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Lea [BlackWhiteConversionMode](../../blackwhiteconversionmode/). El valor predeterminado es [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Observaciones

El siguiente ejemplo muestra cómo establecer el algoritmo de conversión a Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Ver también

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Clase [TiffOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)