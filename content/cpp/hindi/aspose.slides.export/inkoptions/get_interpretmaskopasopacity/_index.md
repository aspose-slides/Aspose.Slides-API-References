---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।
type: docs
weight: 27
url: /hi/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() विधि


ब्रश को रेंडर करने के लिए ROP ऑपरेशन या अपारदर्शिता का उपयोग करता है।

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## टिप्पणी


डिफ़ॉल्ट मान true है। 

अगला उदाहरण दर्शाता है कि कैसे ROP का उपयोग करके [Ink](../../../aspose.slides.ink/) तत्वों को निर्यात करने के लिए सेट किया जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## देखें

* वर्ग [InkOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)