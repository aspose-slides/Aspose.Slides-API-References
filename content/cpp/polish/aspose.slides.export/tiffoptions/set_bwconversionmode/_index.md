---
title: set_BwConversionMode()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy ITiffOptions::get_CompressionType() jest ustawione na TiffCompressionTypes::CCITT4 lub TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Domyślną wartością jest BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /pl/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metoda

Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) jest ustawione na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Domyślną wartością jest [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
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

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Klasa [TiffOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)