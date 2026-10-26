---
title: get_InterpretMaskOpAsOpacity()
second_title: مرجع API Aspose.Slides برای C++
description: از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() متد


از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## یادداشت‌ها


مقدار پیش‌فرض true است. 

مثال بعدی نشان می‌دهد چگونه با استفاده از ROP برای استخراج عناصر [Ink](../../../aspose.slides.ink/) تنظیم شود: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## مراجع

* کلاس [InkOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)