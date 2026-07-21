---
title: MarkdownExportType
second_title: Справка API Aspose.Slides для C++
description: Тип рендеринга документа.
type: docs
weight: 950
url: /ru/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

Тип рендеринга документа.

```cpp
enum class MarkdownExportType
```

### Значения

| Name | Value | Description |
| --- | --- | --- |
| Sequential | 0 | Отрисовывать все элементы отдельно. По одному. |
| TextOnly | 1 | Отрисовывать только текст. |
| Visual | 2 | Отрисовывать все элементы, элементы, сгруппированные — отрисовывать вместе. |

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Смотрите также

* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)