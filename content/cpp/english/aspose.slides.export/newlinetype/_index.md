---
title: NewLineType
second_title: Aspose.Slides for C++ API Reference
description: Type of new line that will be used in generated document.
type: docs
weight: 898
url: /aspose.slides.export/newlinetype/
---
## NewLineType enum


Type of new line that will be used in generated document.

```cpp
enum class NewLineType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS new line - \r |
| Unix | 1 | Unix & Mac OS X new line - |
| Mac | 2 | Mac (OS 9) new line - \r |

## Remarks


Example 
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

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)