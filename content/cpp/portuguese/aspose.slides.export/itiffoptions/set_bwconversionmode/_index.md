---
title: set_BwConversionMode()
second_title: Aspose.Slides para C++ Referência da API
description: "Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se ITiffOptions::get_CompressionType() estiver definido como TiffCompressionTypes::CCITT4 ou TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. O padrão é BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /pt/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) método


Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se [ITiffOptions::get_CompressionType()](../get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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

## Veja Também

* Enumeração [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Classe [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)