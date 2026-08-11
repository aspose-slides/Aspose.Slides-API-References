---
title: set_HideInk()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعرض أو يخفي عناصر الحبر في المستند المُصدَّر.
type: docs
weight: 14
url: /ar/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) طريقة

يعرض أو يخفي عناصر [Ink](../../../aspose.slides.ink/) في المستند المُصدّر.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## ملاحظات

القيمة الافتراضية هي false. 

المثال التالي يوضح كيفية إخفاء عناصر [Ink](../../../aspose.slides.ink/) في المستند PDF المُصدّر: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## انظر أيضًا

* الفئة [InkOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)