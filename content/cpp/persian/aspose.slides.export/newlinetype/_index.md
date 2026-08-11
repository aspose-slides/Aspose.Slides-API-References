---
title: NewLineType
second_title: Aspose.Slides برای C++ مرجع API
description: نوع خط جدیدی که در سند تولید شده استفاده می‌شود.
type: docs
weight: 963
url: /fa/aspose.slides.export/newlinetype/
---
## NewLineType enum

نوع خط جدیدی که در سند تولید شده استفاده می‌شود.

```cpp
enum class NewLineType
```

### مقادیر

| Name | Value | Description |
| --- | --- | --- |
| Windows | 0 | DOS & Windows OS خط جدید - \r\n |
| Unix | 1 | Unix & Mac OS X خط جدید - \n |
| Mac | 2 | Mac (OS 9) خط جدید - \r |

## ملاحظات

مثال
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

## مراجع

* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)