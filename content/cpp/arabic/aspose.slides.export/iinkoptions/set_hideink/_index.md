---
title: set_HideInk()
second_title: مرجع API Aspose.Slides للغة C++
description: يعرض أو يخفي عناصر الحبر في المستند المُصدَّر.
type: docs
weight: 14
url: /ar/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) طريقة

يعرض أو يخفي [Ink](../../../aspose.slides.ink/) عناصر في المستند المُصدَّر.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## ملاحظات

القيمة الافتراضية هي false.

المثال التالي يوضح كيفية إخفاء [Ink](../../../aspose.slides.ink/) عناصر في مستند PDF المُصدَّر:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## انظر أيضًا

* فئة [IInkOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)