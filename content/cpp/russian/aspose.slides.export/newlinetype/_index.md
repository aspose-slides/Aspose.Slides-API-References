---
title: NewLineType
second_title: Aspose.Slides для C++ справочник API
description: Тип символа переноса строки, который будет использоваться в сгенерированном документе.
type: docs
weight: 963
url: /ru/aspose.slides.export/newlinetype/
---
## NewLineType перечисление


Тип символа переноса строки, который будет использоваться в сгенерированном документе.

```cpp
enum class NewLineType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Windows | 0 | Перенос строки DOS и Windows OS – \r\n |
| Unix | 1 | Перенос строки Unix и Mac OS X – \n |
| Mac | 2 | Перенос строки Mac (OS 9) – \r |

## Примечания


Пример
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## См. также

* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)