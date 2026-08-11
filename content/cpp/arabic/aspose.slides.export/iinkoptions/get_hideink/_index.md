---
title: get_HideInk()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعرض أو يخفي عناصر Ink في المستند المُصدَّر.
type: docs
weight: 1
url: /ar/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() طريقة


يعرض أو يخفي عناصر [Ink](../../../aspose.slides.ink/) في المستند المُصدَّر.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## ملاحظات


القيمة الافتراضية هي false. 

المثال التالي يوضح كيفية إخفاء عناصر [Ink](../../../aspose.slides.ink/) في المستند PDF المُصدَّر: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## انظر أيضًا

* الفئة [IInkOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)