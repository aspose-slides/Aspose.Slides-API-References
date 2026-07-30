---
title: set_BwConversionMode()
second_title: Aspose.Slides per C++ Riferimento API
description: "Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se ITiffOptions::get_CompressionType() è impostata su TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Il valore predefinito è BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /it/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metodo

Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [ITiffOptions::get_CompressionType()](../get_compressiontype/) è impostata su [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Il valore predefinito è [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Osservazioni

L'esempio seguente mostra come impostare l'algoritmo di conversione su Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Vedi anche

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Classe [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)