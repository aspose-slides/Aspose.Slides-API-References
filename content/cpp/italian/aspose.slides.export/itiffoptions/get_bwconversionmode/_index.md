---
title: get_BwConversionMode()
second_title: Riferimento API di Aspose.Slides per C++ 
description: "Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se ITiffOptions::get_CompressionType() è impostato su TiffCompressionTypes::CCITT4 o TiffCompressionTypes::CCITT3 Leggi BlackWhiteConversionMode. Il valore predefinito è BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /it/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metodo


Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [ITiffOptions::get_CompressionType()](../get_compressiontype/) è impostato su [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Leggi [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Il valore predefinito è [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Note


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
* Classe [ITiffOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)