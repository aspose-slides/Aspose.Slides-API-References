---
title: get_HideInk()
second_title: Aspose.Slides برای C++ مرجع API
description: عناصر Ink را در سند صادر شده نمایش می‌دهد یا مخفی می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() متد


عناصر [Ink](../../../aspose.slides.ink/) را در سند صادر شده نمایش می‌دهد یا مخفی می‌کند.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## توضیحات


مقدار پیش‌فرض false است. 

مثال بعدی نشان می‌دهد چگونه عناصر [Ink](../../../aspose.slides.ink/) را در سند PDF صادر شده مخفی کنید: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## موارد مرتبط

* کلاس [IInkOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)