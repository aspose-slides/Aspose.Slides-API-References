---
title: get_CompressionLevel()
second_title: Aspose.Slides для C++ справка по API
description: "Указывает уровень сжатия, используемый при сохранении файла презентации. Значение по умолчанию — CompressionLevel::Level6."
type: docs
weight: 79
url: /ru/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() метод


Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Примечания


Более высокие уровни сжатия создают файлы меньшего размера, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержимого презентации.

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Смотрите также

* Перечисление [CompressionLevel](../../compressionlevel/)
* Класс [IPptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)