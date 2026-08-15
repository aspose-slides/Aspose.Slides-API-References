---
title: NewLineType
second_title: Aspose.Slides for C++ API 參考
description: 在產生的文件中將使用的新行類型。
type: docs
weight: 963
url: /zh-hant/aspose.slides.export/newlinetype/
---
## NewLineType enum

在產生的文件中將使用的新行類型。

```cpp
enum class NewLineType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Windows | 0 | DOS 與 Windows OS 新行 - \r\n |
| Unix | 1 | Unix 與 Mac OS X 新行 - \n |
| Mac | 2 | Mac (OS 9) 新行 - \r |

## Remarks

範例 
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

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)