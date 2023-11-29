---
title: MarkdownExportType
second_title: Aspose.Slides for C++ API Reference
description: Type of rendering document.
type: docs
weight: 885
url: /aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum


Type of rendering document.

```cpp
enum class MarkdownExportType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Sequential | 0 | Render all items separately. One by one. |
| TextOnly | 1 | Render only text. |
| Visual | 2 | Render all items, items that are grouped - render together. |

## Remarks


Example: 
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

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)