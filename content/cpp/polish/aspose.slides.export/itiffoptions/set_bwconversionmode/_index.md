---
title: set_BwConversionMode()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Określa algorytm konwertowania obrazu kolorowego na obraz czarno-biały. Opcja ta zostanie zastosowana tylko wtedy, gdy ITiffOptions::get_CompressionType() jest ustawione na TiffCompressionTypes::CCITT4 lub TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Domyślnie jest BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /pl/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) metoda


Określa algorytm konwertowania obrazu kolorowego na obraz czarno-biały. Opcja ta zostanie zastosowana tylko wtedy, gdy [ITiffOptions::get_CompressionType()](../get_compressiontype/) jest ustawione na [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Domyślnie jest [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)