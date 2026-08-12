---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API संदर्भ
description: ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।
type: docs
weight: 40
url: /hi/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) मेथड

ब्रश को रेंडर करने के लिए ROP ऑपरेशन या Opacity का उपयोग करता है।

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## टिप्पणी

डिफ़ॉल्ट मान true है। 

अगला उदाहरण दर्शाता है कि ROP का उपयोग करके [Ink](../../../aspose.slides.ink/) तत्वों को निर्यात करने के लिए कैसे सेट करें: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## और देखें

* क्लास [InkOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)