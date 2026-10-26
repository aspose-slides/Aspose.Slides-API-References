---
title: set_HideInk()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्यात किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छिपाता है।
type: docs
weight: 14
url: /hi/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) विधि


निर्यात दस्तावेज़ में [Ink](../../../aspose.slides.ink/) तत्वों को दिखाता या छिपाता है।

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## टिप्पणी


डिफ़ॉल्ट मान false है। 

अगला उदाहरण दर्शाता है कि निर्यात PDF दस्तावेज़ में [Ink](../../../aspose.slides.ink/) तत्वों को कैसे छिपाया जाए: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## संबंधित देखें

* क्लास [InkOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)