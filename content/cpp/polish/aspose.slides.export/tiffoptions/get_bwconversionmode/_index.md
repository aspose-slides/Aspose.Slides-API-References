---
title: get_BwConversionMode()
second_title: Aspose.Slides dla C++ API Reference
description: "Określa algorytm konwersji obrazu kolorowego na czarno-biały obraz. Ta opcja zostanie zastosowana tylko wtedy, gdy ITiffOptions::get_CompressionType() jest ustawiona na TiffCompressionTypes::CCITT4 lub TiffCompressionTypes::CCITT3. Przeczytaj BlackWhiteConversionMode. Domyślnie jest BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /pl/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() metoda

Określa algorytm konwersji obrazu kolorowego na czarno-biały obraz. Ta opcja zostanie zastosowana tylko wtedy, gdy [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) jest ustawione na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). Przeczytaj [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Domyślnie jest [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
* Klasa [TiffOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)