---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।
type: docs
weight: 40
url: /hi/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) विधि

ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## टिप्पणी

डिफ़ॉल्ट मान true है।

अगला उदाहरण दर्शाता है कि ROP का उपयोग करके [Ink](../../../aspose.slides.ink/) तत्वों को निर्यात करने के लिए कैसे सेट किया जाता है:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## संबंधित देखें

* वर्ग [IInkOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)