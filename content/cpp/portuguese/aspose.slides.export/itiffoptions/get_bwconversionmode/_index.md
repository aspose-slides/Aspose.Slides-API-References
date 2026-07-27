---
title: get_BwConversionMode()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branco. Esta opção será aplicada somente se ITiffOptions::get_CompressionType() estiver definido como TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3. Leia BlackWhiteConversionMode. O padrão é BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /pt/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() método

Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branco. Esta opção será aplicada apenas se [ITiffOptions::get_CompressionType()](../get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Leia [BlackWhiteConversionMode](../../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Observações

O exemplo a seguir mostra como definir o algoritmo de conversão para Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Ver também

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)