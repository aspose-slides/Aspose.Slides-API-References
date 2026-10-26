---
title: get_HideInk()
second_title: Aspose.Slides برای مرجع API C++
description: عناصر Ink را در سند صادر شده نشان می‌دهد یا مخفی می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() متد

عناصر [Ink](../../../aspose.slides.ink/) را در سند صادر شده نشان می‌دهد یا مخفی می‌کند.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## توضیحات

مقدار پیش‌فرض false است.

مثال بعدی نشان می‌دهد که چگونه عناصر [Ink](../../../aspose.slides.ink/) را در سند PDF صادر شده مخفی کنید:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## موارد مرتبط

* کلاس [InkOptions](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)