---
title: Flavor
second_title: Aspose.Slides C++ API Referenciája
description: A programban használt összes markdown specifikáció.
type: docs
weight: 924
url: /hu/aspose.slides.export/flavor/
---
## Íz felsoroló


Minden markdown specifikáció, amely a programban használható.

```cpp
enum class Flavor
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Github | 0 | Github íz. |
| Gruber | 1 | Gruber íz. |
| MultiMarkdown | 2 | Multi markdown íz. |
| CommonMark | 3 | Common mark íz. |
| MarkdownExtra | 4 | Markdown extra íz. |
| Pandoc | 5 | Pandoc íz. |
| Kramdown | 6 | Kramdown íz. |
| Markua | 7 | Markua íz. |
| Maruku | 8 | Maruku íz. |
| Markdown2 | 9 | Markdown2 íz. |
| Remarkable | 10 | Remarkable íz |
| Showdown | 11 | Showdown íz. |
| Ghost | 12 | Ghost íz. |
| GitLab | 13 | Gitlab íz. |
| Haroopad | 14 | Haroopad íz. |
| IaWriter | 15 | IAWriter íz. |
| Redcarpet | 16 | Redcarpet íz. |
| ScholarlyMarkdown | 17 | Scholarly markdown íz. |
| Taiga | 18 | Taiga íz. |
| Trello | 19 | Trello íz. |
| S9ETextFormatter | 20 | S9E text formatter íz. |
| XWiki | 21 | XWiki íz. |
| StackOverflow | 22 | Stack overflow íz. |
| Default | 23 | Alapértelmezett markdown íz. |

## Megjegyzések


Példa: 
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

## Lásd még

* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)