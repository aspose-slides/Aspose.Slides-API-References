---
title: set_BwConversionMode()
second_title: Aspose.Slides для C++ справка по API
description: "Указывает алгоритм преобразования цветного изображения в черно-белое изображение. Этот параметр будет применён только если ITiffOptions::get_CompressionType() установлен в TiffCompressionTypes::CCITT4 или TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. По умолчанию BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /ru/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) метод


Указывает алгоритм преобразования цветного изображения в черно-белое изображение. Этот параметр будет применён только если [ITiffOptions::get_CompressionType()](../get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## Примечания


Следующий пример показывает, как установить алгоритм преобразования в Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## См. также

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)