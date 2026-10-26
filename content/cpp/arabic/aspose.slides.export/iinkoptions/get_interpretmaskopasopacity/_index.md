---
title: get_InterpretMaskOpAsOpacity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستخدم عملية ROP أو Opacity لرسم الفرشاة.
type: docs
weight: 27
url: /ar/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() طريقة

يستخدم عملية ROP أو Opacity لرسم الفرشاة.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## ملاحظات

القيمة الافتراضية هي true.

المثال التالي يوضح كيفية الضبط باستخدام ROP لتصدير عناصر [Ink](../../../aspose.slides.ink/):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## انظر أيضا

* الفئة [IInkOptions](../)
* فضاء الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)