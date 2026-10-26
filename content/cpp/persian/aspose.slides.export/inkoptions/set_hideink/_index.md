---
title: set_HideInk()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش یا مخفی کردن عناصر Ink در سند صادر شده.
type: docs
weight: 14
url: /fa/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) متد


نمایش یا مخفی کردن [Ink](../../../aspose.slides.ink/) عناصر در سند صادر شده.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## توضیحات


مقدار پیش‌فرض false است. 

مثال بعدی نشان می‌دهد چگونه [Ink](../../../aspose.slides.ink/) عناصر را در سند PDF صادر شده مخفی کنید: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## مراجع

* کلاس [InkOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)