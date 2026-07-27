---
title: get_BwConversionMode()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica el algoritmo para convertir una imagen en color a una imagen en blanco y negro. Esta opción se aplicará solo si ITiffOptions::get_CompressionType() está configurado a TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3. Leer BlackWhiteConversionMode. El valor predeterminado es BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /es/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() método


Especifica el algoritmo para convertir una imagen en color a una imagen en blanco y negro. Esta opción se aplicará solo si [ITiffOptions::get_CompressionType()](../get_compressiontype/) está configurado a [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Leer [BlackWhiteConversionMode](../../blackwhiteconversionmode/). El valor predeterminado es [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
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
* Clase [ITiffOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)