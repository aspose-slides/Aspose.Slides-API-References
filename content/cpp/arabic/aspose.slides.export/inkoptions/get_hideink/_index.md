---
title: get_HideInk()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعرض أو يخفي عناصر الحبر في المستند المُصدَّر.
type: docs
weight: 1
url: /ar/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() طريقة

يعرض أو يخفي عناصر [Ink](../../../aspose.slides.ink/) في المستند المُصدَّر.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## ملاحظات

القيمة الافتراضية هي false. 

المثال التالي يوضح كيفية إخفاء عناصر [Ink](../../../aspose.slides.ink/) في مستند PDF المُصدَّر: 
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