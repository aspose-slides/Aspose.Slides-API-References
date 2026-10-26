---
title: Flavor
second_title: Aspose.Slides for C++ API 参考
description: 程序中使用的所有 Markdown 规范。
type: docs
weight: 924
url: /zh/aspose.slides.export/flavor/
---
## Flavor 枚举

程序中使用的所有 Markdown 规范。

```cpp
enum class Flavor
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Github | 0 | Github 风格。 |
| Gruber | 1 | Gruber 风格。 |
| MultiMarkdown | 2 | Multi markdown 风格。 |
| CommonMark | 3 | Common mark 风格。 |
| MarkdownExtra | 4 | Markdown extra 风格。 |
| Pandoc | 5 | Pandoc 风格。 |
| Kramdown | 6 | Kramdown 风格。 |
| Markua | 7 | Markua 风格。 |
| Maruku | 8 | Maruku 风格。 |
| Markdown2 | 9 | Markdown2 风格。 |
| Remarkable | 10 | Remarkable 风格 |
| Showdown | 11 | Showdown 风格。 |
| Ghost | 12 | Ghost 风格。 |
| GitLab | 13 | Gitlab 风格。 |
| Haroopad | 14 | Haroopad 风格。 |
| IaWriter | 15 | IAWriter 风格。 |
| Redcarpet | 16 | Redcarpet 风格。 |
| ScholarlyMarkdown | 17 | Scholarly markdown 风格。 |
| Taiga | 18 | Taiga 风格。 |
| Trello | 19 | Trello 风格。 |
| S9ETextFormatter | 20 | S9E text formatter 风格。 |
| XWiki | 21 | XWiki 风格。 |
| StackOverflow | 22 | Stack overflow 风格。 |
| Default | 23 | Default markdown 风格。 |

## 备注

示例：
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

## 另见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)