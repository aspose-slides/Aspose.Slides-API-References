---
title: set_IncludeOleData()
second_title: Aspose.Slides برای مرجع API C++
description: True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی. نوشتن bool.
type: docs
weight: 469
url: /fa/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) متد


برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی، مقدار true را تنظیم کنید. نوشتن **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* کلاس [IPdfOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)