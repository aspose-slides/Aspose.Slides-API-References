---
title: set_HideInk()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्यात किए गए दस्तावेज़ में इंक तत्वों को दिखाता या छुपाता है।
type: docs
weight: 14
url: /hi/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) विधि


बाहर निकाले गए दस्तावेज़ में [Ink](../../../aspose.slides.ink/) तत्वों को दिखाता या छुपाता है।

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## टिप्पणी


डिफ़ॉल्ट मान false है। 

अगला उदाहरण दिखाता है कि कैसे [Ink](../../../aspose.slides.ink/) तत्वों को निर्यात किए गए PDF दस्तावेज़ में छुपाया जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## देखें

* क्लास [IInkOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)