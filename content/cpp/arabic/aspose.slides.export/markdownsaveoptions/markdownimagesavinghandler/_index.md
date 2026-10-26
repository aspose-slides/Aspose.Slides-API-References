---
title: MarkdownImageSavingHandler
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتم استدعاؤه لكل صورة غير SVG (bitmap أو metafile) أثناء تصدير Markdown. أعد true لاستخدام الرابط المحدد، أو false لتطبيق منطق الحفظ الافتراضي.
type: docs
weight: 300
url: /ar/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


يتم استدعاؤه لكل صورة غير SVG (bitmap أو metafile) أثناء تصدير Markdown. 

أعد **true** لاستخدام *رابط* المحدد،

أو **false** لتطبيق منطق الحفظ الافتراضي.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## انظر أيضًا

* فئة [MarkdownSaveOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)