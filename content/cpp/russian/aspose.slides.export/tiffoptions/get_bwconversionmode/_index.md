---
title: get_BwConversionMode()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает алгоритм преобразования цветного изображения в черно-белое изображение. Этот параметр будет применяться только если ITiffOptions::get_CompressionType() установлен в TiffCompressionTypes::CCITT4 или TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. По умолчанию BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /ru/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() метод


Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применяться только в том случае, если [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). См. [BlackWhiteConversionMode](../../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## Замечания


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
* Класс [TiffOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)