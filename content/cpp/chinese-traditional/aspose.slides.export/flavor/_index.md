---
title: Flavor
second_title: Aspose.Slides for C++ API 參考
description: 程式中使用的所有 Markdown 規範。
type: docs
weight: 924
url: /zh-hant/aspose.slides.export/flavor/
---
## Flavor 列舉

All markdown specifications used in program.

```cpp
enum class Flavor
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Github | 0 | Github 風格。 |
| Gruber | 1 | Gruber 風格。 |
| MultiMarkdown | 2 | Multi markdown 風格。 |
| CommonMark | 3 | Common mark 風格。 |
| MarkdownExtra | 4 | Markdown extra 風格。 |
| Pandoc | 5 | Pandoc 風格。 |
| Kramdown | 6 | Kramdown 風格。 |
| Markua | 7 | Markua 風格。 |
| Maruku | 8 | Maruku 風格。 |
| Markdown2 | 9 | Markdown2 風格。 |
| Remarkable | 10 | Remarkable 風格 |
| Showdown | 11 | Showdown 風格。 |
| Ghost | 12 | Ghost 風格。 |
| GitLab | 13 | Gitlab 風格。 |
| Haroopad | 14 | Haroopad 風格。 |
| IaWriter | 15 | IAWriter 風格。 |
| Redcarpet | 16 | Redcarpet 風格。 |
| ScholarlyMarkdown | 17 | Scholarly markdown 風格。 |
| Taiga | 18 | Taiga 風格。 |
| Trello | 19 | Trello 風格。 |
| S9ETextFormatter | 20 | S9E text formatter 風格。 |
| XWiki | 21 | XWiki 風格。 |
| StackOverflow | 22 | Stack overflow 風格。 |
| Default | 23 | 預設 markdown 風格。 |

## 備註

範例：
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

## 另請參閱

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)