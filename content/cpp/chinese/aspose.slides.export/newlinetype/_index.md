---
title: NewLineType
second_title: Aspose.Slides for C++ API 参考
description: 生成的文档中将使用的新行类型。
type: docs
weight: 963
url: /zh/aspose.slides.export/newlinetype/
---
## NewLineType 枚举

生成的文档中将使用的新行类型。

```cpp
enum class NewLineType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Windows | 0 | DOS 和 Windows OS 换行符 - \r\n |
| Unix | 1 | Unix 和 Mac OS X 换行符 - \n |
| Mac | 2 | Mac (OS 9) 换行符 - \r |

## 备注

示例
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