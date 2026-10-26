---
title: get_IncludeOleData()
second_title: Aspose.Slides برای مرجع API C++
description: True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های توکار در PDF خروجی. خواندن bool.
type: docs
weight: 456
url: /fa/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() متد

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های توکار در PDF خروجی. قابل خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

## مراجع

* کلاس [IPdfOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)