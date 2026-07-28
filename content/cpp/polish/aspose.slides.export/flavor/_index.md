---
title: Flavor
second_title: Aspose.Slides dla C++ - referencja API
description: Wszystkie specyfikacje markdown używane w programie.
type: docs
weight: 924
url: /pl/aspose.slides.export/flavor/
---
## Flavor enum


Wszystkie specyfikacje markdown używane w programie.

```cpp
enum class Flavor
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Github | 0 | smak Github. |
| Gruber | 1 | smak Gruber. |
| MultiMarkdown | 2 | smak Multi markdown. |
| CommonMark | 3 | smak Common mark. |
| MarkdownExtra | 4 | smak Markdown extra. |
| Pandoc | 5 | smak Pandoc. |
| Kramdown | 6 | smak Kramdown. |
| Markua | 7 | smak Markua. |
| Maruku | 8 | smak Maruku. |
| Markdown2 | 9 | smak Markdown2. |
| Remarkable | 10 | smak Remarkable |
| Showdown | 11 | smak Showdown. |
| Ghost | 12 | smak Ghost. |
| GitLab | 13 | smak Gitlab. |
| Haroopad | 14 | smak Haroopad. |
| IaWriter | 15 | smak IAWriter. |
| Redcarpet | 16 | smak Redcarpet. |
| ScholarlyMarkdown | 17 | smak Scholarly markdown. |
| Taiga | 18 | smak Taiga. |
| Trello | 19 | smak Trello. |
| S9ETextFormatter | 20 | smak S9E text formatter. |
| XWiki | 21 | smak XWiki. |
| StackOverflow | 22 | smak Stack overflow. |
| Default | 23 | domyślny smak markdown. |

## Remarks


Przykład:
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

## See Also

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)