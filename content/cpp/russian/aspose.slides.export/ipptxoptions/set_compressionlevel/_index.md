---
title: set_CompressionLevel()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — CompressionLevel::Level6."
type: docs
weight: 92
url: /ru/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) method


Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Remarks


Более высокие уровни сжатия создают более небольшие файлы, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержания презентации. 

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## See Also

* Enum [CompressionLevel](../../compressionlevel/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)