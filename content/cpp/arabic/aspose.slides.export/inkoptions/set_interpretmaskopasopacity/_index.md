---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يستخدم عملية ROP أو الشفافية لتصوير الفرشاة.
type: docs
weight: 40
url: /ar/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) طريقة


يستخدم عملية ROP أو الشفافية لتصوير الفرشاة.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

* فئة [InkOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)