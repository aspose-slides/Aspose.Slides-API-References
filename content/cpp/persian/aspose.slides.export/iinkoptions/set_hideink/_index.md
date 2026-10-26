---
title: set_HideInk()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایش یا پنهان‌سازی عناصر جوهر در سند صادر شده.
type: docs
weight: 14
url: /fa/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) متد


نمایش یا پنهان‌کردن [Ink](../../../aspose.slides.ink/) عناصر در سند صادر شده.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## ملاحظات


مقدار پیش‌فرض false است.

مثال بعدی نشان می‌دهد چگونه [Ink](../../../aspose.slides.ink/) عناصر را در سند PDF صادر شده پنهان کنید:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## مراجع دیگر

* کلاس [IInkOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)