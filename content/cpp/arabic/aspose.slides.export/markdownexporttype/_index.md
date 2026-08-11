---
title: MarkdownExportType
second_title: مرجع API Aspose.Slides للغة C++
description: نوع المستند المُصدّر.
type: docs
weight: 950
url: /ar/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

نوع المستند المُصدّر.

```cpp
enum class MarkdownExportType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Sequential | 0 | قم بتصيير جميع العناصر بشكل منفصل. واحدًا تلو الآخر. |
| TextOnly | 1 | قم بتصيير النص فقط. |
| Visual | 2 | قم بتصيير جميع العناصر، العناصر التي تم تجميعها – تصييرها معًا. |

## الملاحظات

مثال:
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

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)