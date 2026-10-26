---
title: set_IncludeOleData()
second_title: Aspose.Slides برای C++ مرجع API
description: True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF تولید-شده. **bool** بنویسید.
type: docs
weight: 469
url: /fa/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) متد

True برای تبدیل همه داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF تولید-شده. **bool** بنویسید.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)