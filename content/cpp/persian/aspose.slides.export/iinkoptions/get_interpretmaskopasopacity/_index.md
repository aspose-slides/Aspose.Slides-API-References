---
title: get_InterpretMaskOpAsOpacity()
second_title: مرجع API Aspose.Slides برای C++
description: از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() متد


از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## توضیحات


مقدار پیش‌فرض true است.

مثال بعدی نشان می‌دهد که چگونه با استفاده از ROP برای صادرات عناصر [Ink](../../../aspose.slides.ink/) تنظیم می‌شود: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## مراجع

* کلاس [IInkOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)