---
title: set_InterpretMaskOpAsOpacity()
second_title: مرجع API Aspose.Slides برای C++
description: از عملیات ROP یا شفافیت برای رندر کردن براش استفاده می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) متد


از عملیات ROP یا شفافیت برای رندر کردن براش استفاده می‌کند.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## توضیحات


مقدار پیش‌فرض true است.

مثال بعدی نشان می‌دهد که چگونه با استفاده از ROP برای استخراج عناصر [Ink](../../../aspose.slides.ink/) تنظیم می‌شود:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## همچنین ببینید

* کلاس [InkOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)