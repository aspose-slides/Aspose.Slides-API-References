---
title: MarkdownExportType
second_title: مرجع API Aspose.Slides برای C++
description: نوع رندر سند.
type: docs
weight: 950
url: /fa/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

نوع رندر سند.

```cpp
enum class MarkdownExportType
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Sequential | 0 | تمام آیتم‌ها را به طور جداگانه رندر می‌کند. یکی‌به‌یکی. |
| TextOnly | 1 | فقط متن را رندر می‌کند. |
| Visual | 2 | تمام آیتم‌ها را رندر می‌کند، آیتم‌های گروه‌بندی شده - به‌صورت مشترک رندر می‌شوند. |

## توضیحات

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

## موارد مرتبط

* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)