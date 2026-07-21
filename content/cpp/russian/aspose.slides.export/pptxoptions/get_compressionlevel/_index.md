---
title: get_CompressionLevel()
second_title: Aspose.Slides для C++ справочник API
description: "Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию равно CompressionLevel::Level6."
type: docs
weight: 79
url: /ru/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() метод


Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Примечания


Более высокие уровни сжатия дают меньший размер файлов, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержимого презентации. 

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Смотрите также

* Enum [CompressionLevel](../../compressionlevel/)
* Класс [PptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)