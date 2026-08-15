---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API 參考
description: 文件渲染的類型。
type: docs
weight: 950
url: /zh-hant/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType 列舉


文件渲染的類型。

```cpp
enum class MarkdownExportType
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Sequential | 0 | 分別渲染所有項目。一次一個。 |
| TextOnly | 1 | 僅渲染文字。 |
| Visual | 2 | 渲染所有項目，已分組的項目一起渲染。 |

## 備註


範例：
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

## 另請參閱

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)