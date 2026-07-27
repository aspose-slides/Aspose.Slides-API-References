---
title: set_BwConversionMode()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se ITiffOptions::get_CompressionType() estiver definido como TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. O padrão é BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /pt/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) método


Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
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

## Veja também

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Classe [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)