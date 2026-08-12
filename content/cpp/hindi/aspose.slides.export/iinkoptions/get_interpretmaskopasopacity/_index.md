---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।
type: docs
weight: 27
url: /hi/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() मेथड

ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## टिप्पणियाँ

डिफ़ॉल्ट मान true है।

आगामी उदाहरण दिखाता है कि [Ink](../../../aspose.slides.ink/) तत्वों को निर्यात करने के लिए ROP का उपयोग कैसे सेट किया जाए:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## सम्बंधित

* क्लास [IInkOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)