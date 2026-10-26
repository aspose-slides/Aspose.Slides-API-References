---
title: set_BwConversionMode()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica el algoritmo para convertir una imagen en color a una imagen en blanco y negro. Esta opción se aplicará solo si ITiffOptions::get_CompressionType() está configurado a TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. El valor predeterminado es BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /es/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) método

Especifica el algoritmo para convertir una imagen en color a una imagen en blanco y negro. Esta opción se aplicará solo si [ITiffOptions::get_CompressionType()](../get_compressiontype/) está configurado a [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). El valor predeterminado es [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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

## Véase también

* Enumeración [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Clase [ITiffOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)