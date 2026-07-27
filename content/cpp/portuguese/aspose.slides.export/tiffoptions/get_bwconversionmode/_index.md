---
title: get_BwConversionMode()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branco. Esta opção será aplicada somente se ITiffOptions::get_CompressionType() estiver definido como TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. O padrão é BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /pt/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() método

Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branco. Esta opção será aplicada somente se [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Read [BlackWhiteConversionMode](../../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
* Classe [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)