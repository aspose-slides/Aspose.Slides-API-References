---
title: Flavor
second_title: Справочник API Aspose.Slides для C++
description: Все спецификации markdown, используемые в программе.
type: docs
weight: 924
url: /ru/aspose.slides.export/flavor/
---
## Перечисление Flavor


Все спецификации markdown, используемые в программе.

```cpp
enum class Flavor
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Github | 0 | Вариант Github. |
| Gruber | 1 | Вариант Gruber. |
| MultiMarkdown | 2 | Вариант Multi markdown. |
| CommonMark | 3 | Вариант Common mark. |
| MarkdownExtra | 4 | Вариант Markdown extra. |
| Pandoc | 5 | Вариант Pandoc. |
| Kramdown | 6 | Вариант Kramdown. |
| Markua | 7 | Вариант Markua. |
| Maruku | 8 | Вариант Maruku. |
| Markdown2 | 9 | Вариант Markdown2. |
| Remarkable | 10 | Вариант Remarkable |
| Showdown | 11 | Вариант Showdown. |
| Ghost | 12 | Вариант Ghost. |
| GitLab | 13 | Вариант Gitlab. |
| Haroopad | 14 | Вариант Haroopad. |
| IaWriter | 15 | Вариант IAWriter. |
| Redcarpet | 16 | Вариант Redcarpet. |
| ScholarlyMarkdown | 17 | Вариант Scholarly markdown. |
| Taiga | 18 | Вариант Taiga. |
| Trello | 19 | Вариант Trello. |
| S9ETextFormatter | 20 | Вариант S9E text formatter. |
| XWiki | 21 | Вариант XWiki. |
| StackOverflow | 22 | Вариант Stack overflow. |
| Default | 23 | Вариант Default markdown. |

## Примечания


Пример: 
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