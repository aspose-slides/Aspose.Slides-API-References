---
title: set_BwConversionMode()
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se ITiffOptions::get_CompressionType() è impostato su TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Il valore predefinito è BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /it/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metodo

Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) è impostato su [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Il valore predefinito è [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Osservazioni

Il seguente esempio mostra come impostare l'algoritmo di conversione su Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Vedi anche

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Classe [TiffOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)