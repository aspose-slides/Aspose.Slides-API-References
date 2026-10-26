---
title: get_IncludeOleData()
second_title: Aspose.Slides برای C++ مرجع API
description: True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی. خواندن bool.
type: docs
weight: 456
url: /fa/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() متد

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF خروجی. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## توضیحات

پیش‌فرض **false** است. 

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## موارد مرتبط

* کلاس [PdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)