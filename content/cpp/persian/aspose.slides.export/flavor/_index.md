---
title: Flavor
second_title: مرجع API Aspose.Slides برای C++
description: تمام مشخصات markdown که در برنامه استفاده می‌شود.
type: docs
weight: 924
url: /fa/aspose.slides.export/flavor/
---
## Flavor enum

تمام مشخصات markdown که در برنامه استفاده می‌شود.

```cpp
enum class Flavor
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Github | 0 | طعم Github. |
| Gruber | 1 | طعم Gruber. |
| MultiMarkdown | 2 | طعم Multi markdown. |
| CommonMark | 3 | طعم Common mark. |
| MarkdownExtra | 4 | طعم Markdown extra. |
| Pandoc | 5 | طعم Pandoc. |
| Kramdown | 6 | طعم Kramdown. |
| Markua | 7 | طعم Markua. |
| Maruku | 8 | طعم Maruku. |
| Markdown2 | 9 | طعم Markdown2. |
| Remarkable | 10 | طعم Remarkable |
| Showdown | 11 | طعم Showdown. |
| Ghost | 12 | طعم Ghost. |
| GitLab | 13 | طعم Gitlab. |
| Haroopad | 14 | طعم Haroopad. |
| IaWriter | 15 | طعم IAWriter. |
| Redcarpet | 16 | طعم Redcarpet. |
| ScholarlyMarkdown | 17 | طعم Scholarly markdown. |
| Taiga | 18 | طعم Taiga. |
| Trello | 19 | طعم Trello. |
| S9ETextFormatter | 20 | طعم S9E text formatter. |
| XWiki | 21 | طعم XWiki. |
| StackOverflow | 22 | طعم Stack overflow. |
| Default | 23 | طعم Default markdown. |

## توضیحات

مثال: 
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

## مراجع

* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)