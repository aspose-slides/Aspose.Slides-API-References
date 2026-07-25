---
title: MarkdownExportType
second_title: C++ 用 Aspose.Slides API リファレンス
description: ドキュメントのレンダリングタイプ。
type: docs
weight: 950
url: /ja/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType 列挙型

ドキュメントのレンダリングタイプ。

```cpp
enum class MarkdownExportType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Sequential | 0 | すべての項目を個別にレンダリングします。1つずつ。 |
| TextOnly | 1 | テキストのみをレンダリングします。 |
| Visual | 2 | すべての項目をレンダリングし、グループ化された項目は一緒にレンダリングします。 |

## 備考

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)