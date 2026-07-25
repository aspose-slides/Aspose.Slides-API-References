---
title: Flavor
second_title: Aspose.Slides for C++ API リファレンス
description: プログラムで使用されるすべての Markdown 仕様。
type: docs
weight: 924
url: /ja/aspose.slides.export/flavor/
---
## Flavor 列挙型

プログラムで使用されるすべての Markdown 仕様。

```cpp
enum class Flavor
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Github | 0 | Github フレーバー。 |
| Gruber | 1 | Gruber フレーバー。 |
| MultiMarkdown | 2 | Multi markdown フレーバー。 |
| CommonMark | 3 | Common mark フレーバー。 |
| MarkdownExtra | 4 | Markdown extra フレーバー。 |
| Pandoc | 5 | Pandoc フレーバー。 |
| Kramdown | 6 | Kramdown フレーバー。 |
| Markua | 7 | Markua フレーバー。 |
| Maruku | 8 | Maruku フレーバー。 |
| Markdown2 | 9 | Markdown2 フレーバー。 |
| Remarkable | 10 | Remarkable フレーバー |
| Showdown | 11 | Showdown フレーバー。 |
| Ghost | 12 | Ghost フレーバー。 |
| GitLab | 13 | Gitlab フレーバー。 |
| Haroopad | 14 | Haroopad フレーバー。 |
| IaWriter | 15 | IAWriter フレーバー。 |
| Redcarpet | 16 | Redcarpet フレーバー。 |
| ScholarlyMarkdown | 17 | Scholarly markdown フレーバー。 |
| Taiga | 18 | Taiga フレーバー。 |
| Trello | 19 | Trello フレーバー。 |
| S9ETextFormatter | 20 | S9E text formatter フレーバー。 |
| XWiki | 21 | XWiki フレーバー。 |
| StackOverflow | 22 | Stack overflow フレーバー。 |
| Default | 23 | Default markdown フレーバー。 |

## 備考

例:
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

## 関連項目

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)