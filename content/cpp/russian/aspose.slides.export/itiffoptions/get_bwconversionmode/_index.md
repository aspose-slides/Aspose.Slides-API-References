---
title: get_BwConversionMode()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает алгоритм преобразования цветного изображения в черно-белое изображение. Этот параметр будет применяться только если ITiffOptions::get_CompressionType() установлен в TiffCompressionTypes::CCITT4 или TiffCompressionTypes::CCITT3. Читайте BlackWhiteConversionMode. По умолчанию BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /ru/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() метод

Указывает алгоритм преобразования цветного изображения в черно-белое изображение. Этот параметр будет применяться только если [ITiffOptions::get_CompressionType()](../get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/). Читайте [BlackWhiteConversionMode](../../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
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
* Класс [ITiffOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)