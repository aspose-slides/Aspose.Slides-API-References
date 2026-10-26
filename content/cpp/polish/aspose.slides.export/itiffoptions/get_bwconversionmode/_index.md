---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ Referencja API
description: "Określa algorytm konwertowania obrazu kolorowego na czarno-biały obraz. Ta opcja zostanie zastosowana tylko wtedy, gdy ITiffOptions::get_CompressionType() jest ustawiony na TiffCompressionTypes::CCITT4 lub TiffCompressionTypes::CCITT3. Przeczytaj BlackWhiteConversionMode. Domyślnie jest BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /pl/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() metoda


Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy [ITiffOptions::get_CompressionType()](../get_compressiontype/) jest ustawiony na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). Przeczytaj [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Domyślnie jest [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Uwagi


Poniższy przykład pokazuje, jak ustawić algorytm konwersji na Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Zobacz także

* Wyliczenie [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasa [ITiffOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)