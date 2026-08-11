---
title: get_InterpretMaskOpAsOpacity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستخدم عملية ROP أو الشفافية لتصيير الفرشاة.
type: docs
weight: 27
url: /ar/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() طريقة

يستخدم عملية ROP أو الشفافية لتصيير الفرشاة.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
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

## انظر أيضًا

* الفئة [InkOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)