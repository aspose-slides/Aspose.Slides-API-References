---
title: set_BwConversionMode()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применён только если ITiffOptions::get_CompressionType() установлен в TiffCompressionTypes::CCITT4 или TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. По умолчанию BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /ru/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) метод

Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применён только если [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Примечания

Следующий пример показывает, как задать алгоритм преобразования в Dithering.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Смотрите также

* Перечисление [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Класс [TiffOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)