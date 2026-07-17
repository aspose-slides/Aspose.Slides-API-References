---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API 参考
description: 文档渲染的类型。
type: docs
weight: 950
url: /zh/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType 枚举

文档渲染的类型。

```cpp
enum class MarkdownExportType
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Sequential | 0 | 逐个分别渲染所有项目。一次一个。 |
| TextOnly | 1 | 仅渲染文本。 |
| Visual | 2 | 渲染所有项目，分组的项目一起渲染。 |

## 备注

示例： 
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

## 另见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)