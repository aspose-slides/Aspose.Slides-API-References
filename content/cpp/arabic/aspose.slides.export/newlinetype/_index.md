---
title: NewLineType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: نوع سطر جديد سيتم استخدامه في المستند المُولَّد.
type: docs
weight: 963
url: /ar/aspose.slides.export/newlinetype/
---
## NewLineType enum

نوع سطر جديد سيتم استخدامه في المستند المُنشئ.

```cpp
enum class NewLineType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Windows | 0 | سطر جديد لنظام DOS و Windows OS - \r\n |
| Unix | 1 | سطر جديد لنظام Unix و Mac OS X - \n |
| Mac | 2 | سطر جديد لنظام Mac (OS 9) - \r |

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

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)