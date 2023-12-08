---
title: Flavor
second_title: Aspose.Slides for C++ API Reference
description: All markdown specifications used in program.
type: docs
weight: 937
url: /aspose.slides.export/flavor/
---
## Flavor enum


All markdown specifications used in program.

```cpp
enum class Flavor
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Github | 0 | Github flavor. |
| Gruber | 1 | Gruber flavor. |
| MultiMarkdown | 2 | Multi markdown flavor. |
| CommonMark | 3 | Common mark flavor. |
| MarkdownExtra | 4 | Markdown extra flavor. |
| Pandoc | 5 | Pandoc flavor. |
| Kramdown | 6 | Kramdown flavor. |
| Markua | 7 | Markua flavor. |
| Maruku | 8 | Maruku flavor. |
| Markdown2 | 9 | Markdown2 flavor. |
| Remarkable | 10 | Remarkable flavor |
| Showdown | 11 | Showdown flavor. |
| Ghost | 12 | Ghost flavor. |
| GitLab | 13 | Gitlab flavor. |
| Haroopad | 14 | Haroopad flavor. |
| IaWriter | 15 | IAWriter flavor. |
| Redcarpet | 16 | Redcarpet flavor. |
| ScholarlyMarkdown | 17 | Scholarly markdown flavor. |
| Taiga | 18 | Taiga flavor. |
| Trello | 19 | Trello flavor. |
| S9ETextFormatter | 20 | S9E text formatter flavor. |
| XWiki | 21 | XWiki flavor. |
| StackOverflow | 22 | Stack overflow flavor. |
| Default | 23 | Default markdown flavor. |

## Remarks


Example: 
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

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)