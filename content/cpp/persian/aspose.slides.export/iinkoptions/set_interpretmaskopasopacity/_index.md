---
title: set_InterpretMaskOpAsOpacity()
second_title: مرجع API Aspose.Slides برای C++ 
description: از عملیات ROP یا شفافیت برای رندر کردن براش استفاده می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) متد


از عملیات ROP یا شفافیت برای رندر کردن براش استفاده می‌کند.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## توضیحات


مقدار پیش‌فرض برابر با true است. 

مثال بعدی نشان می‌دهد چگونه با استفاده از ROP برای صادر کردن عناصر [Ink](../../../aspose.slides.ink/) تنظیم شود: 
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