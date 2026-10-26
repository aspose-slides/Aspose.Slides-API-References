---
title: Flavor
second_title: Aspose.Slides för C++ API-referens
description: Alla markdown-specifikationer som används i programmet.
type: docs
weight: 924
url: /sv/aspose.slides.export/flavor/
---
## Flavor enum

Alla markdown-specifikationer som används i programmet.

```cpp
enum class Flavor
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Github | 0 | Github-smak. |
| Gruber | 1 | Gruber-smak. |
| MultiMarkdown | 2 | Multi markdown-smak. |
| CommonMark | 3 | Common mark-smak. |
| MarkdownExtra | 4 | Markdown extra-smak. |
| Pandoc | 5 | Pandoc-smak. |
| Kramdown | 6 | Kramdown-smak. |
| Markua | 7 | Markua-smak. |
| Maruku | 8 | Maruku-smak. |
| Markdown2 | 9 | Markdown2-smak. |
| Remarkable | 10 | Remarkable-smak |
| Showdown | 11 | Showdown-smak. |
| Ghost | 12 | Ghost-smak. |
| GitLab | 13 | Gitlab-smak. |
| Haroopad | 14 | Haroopad-smak. |
| IaWriter | 15 | IAWriter-smak. |
| Redcarpet | 16 | Redcarpet-smak. |
| ScholarlyMarkdown | 17 | Scholarly markdown-smak. |
| Taiga | 18 | Taiga-smak. |
| Trello | 19 | Trello-smak. |
| S9ETextFormatter | 20 | S9E text formatter-smak. |
| XWiki | 21 | XWiki-smak. |
| StackOverflow | 22 | Stack overflow-smak. |
| Default | 23 | Default markdown-smak. |

## Anmärkningar

Exempel:
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

## Se också

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)