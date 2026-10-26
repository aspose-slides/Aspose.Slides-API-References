---
title: Flavor
second_title: مرجع API لـ Aspose.Slides للـ C++
description: جميع مواصفات markdown المستخدمة في البرنامج.
type: docs
weight: 924
url: /ar/aspose.slides.export/flavor/
---
## Flavor تعداد

All markdown specifications used in program.

```cpp
enum class Flavor
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Github | 0 | Github نمط. |
| Gruber | 1 | Gruber نمط. |
| MultiMarkdown | 2 | Multi markdown نمط. |
| CommonMark | 3 | Common mark نمط. |
| MarkdownExtra | 4 | Markdown extra نمط. |
| Pandoc | 5 | Pandoc نمط. |
| Kramdown | 6 | Kramdown نمط. |
| Markua | 7 | Markua نمط. |
| Maruku | 8 | Maruku نمط. |
| Markdown2 | 9 | Markdown2 نمط. |
| Remarkable | 10 | Remarkable نمط |
| Showdown | 11 | Showdown نمط. |
| Ghost | 12 | Ghost نمط. |
| GitLab | 13 | Gitlab نمط. |
| Haroopad | 14 | Haroopad نمط. |
| IaWriter | 15 | IAWriter نمط. |
| Redcarpet | 16 | Redcarpet نمط. |
| ScholarlyMarkdown | 17 | Scholarly markdown نمط. |
| Taiga | 18 | Taiga نمط. |
| Trello | 19 | Trello نمط. |
| S9ETextFormatter | 20 | S9E text formatter نمط. |
| XWiki | 21 | XWiki نمط. |
| StackOverflow | 22 | Stack overflow نمط. |
| Default | 23 | Default markdown نمط. |

## ملاحظات


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

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)