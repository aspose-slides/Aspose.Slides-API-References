---
title: set_InterpretMaskOpAsOpacity()
second_title: مرجع API Aspose.Slides للغة C++
description: يستخدم عملية ROP أو الشفافية لرسم الفرشاة.
type: docs
weight: 40
url: /ar/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) طريقة


يستخدم عملية ROP أو الشفافية لرسم الفرشاة.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## ملاحظات


القيمة الافتراضية هي true. 

المثال التالي يوضح كيفية الإعداد باستخدام ROP لتصدير عناصر [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## انظر أيضًا

* الفئة [IInkOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)