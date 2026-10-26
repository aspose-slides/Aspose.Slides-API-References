---
title: set_CompressionLevel()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает уровень сжатия, используемый при сохранении презентационного документа. Значение по умолчанию — CompressionLevel::Level6."
type: docs
weight: 92
url: /ru/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) метод

Указывает уровень сжатия, используемый при сохранении презентационного документа. Значение по умолчанию — [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Примечания

Более высокие уровни сжатия создают более маленькие файлы, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержимого презентации.  

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## См. также

* Перечисление [CompressionLevel](../../compressionlevel/)
* Класс [PptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)