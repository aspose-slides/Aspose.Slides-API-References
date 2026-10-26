---
title: Flavor
second_title: Aspose.Slides pro C++ API Reference
description: Všechny specifikace markdown používané v programu.
type: docs
weight: 924
url: /cs/aspose.slides.export/flavor/
---
## Výčet Flavor

Všechny specifikace markdown používané v programu.

```cpp
enum class Flavor
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Github | 0 | varianta Github. |
| Gruber | 1 | varianta Gruber. |
| MultiMarkdown | 2 | varianta Multi markdown. |
| CommonMark | 3 | varianta Common mark. |
| MarkdownExtra | 4 | varianta Markdown extra. |
| Pandoc | 5 | varianta Pandoc. |
| Kramdown | 6 | varianta Kramdown. |
| Markua | 7 | varianta Markua. |
| Maruku | 8 | varianta Maruku. |
| Markdown2 | 9 | varianta Markdown2. |
| Remarkable | 10 | varianta Remarkable |
| Showdown | 11 | varianta Showdown. |
| Ghost | 12 | varianta Ghost. |
| GitLab | 13 | varianta Gitlab. |
| Haroopad | 14 | varianta Haroopad. |
| IaWriter | 15 | varianta IAWriter. |
| Redcarpet | 16 | varianta Redcarpet. |
| ScholarlyMarkdown | 17 | varianta Scholarly markdown. |
| Taiga | 18 | varianta Taiga. |
| Trello | 19 | varianta Trello. |
| S9ETextFormatter | 20 | varianta S9E text formatter. |
| XWiki | 21 | varianta XWiki. |
| StackOverflow | 22 | varianta Stack overflow. |
| Default | 23 | varianta Default markdown. |

## Poznámky

Příklad: 
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

## Viz také

* jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)