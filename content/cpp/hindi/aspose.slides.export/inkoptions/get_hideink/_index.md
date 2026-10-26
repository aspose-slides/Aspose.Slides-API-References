---
title: get_HideInk()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्यातित दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है।
type: docs
weight: 1
url: /hi/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() मेथड


निर्यातित दस्तावेज़ में [Ink](../../../aspose.slides.ink/) तत्वों को दिखाता या छुपाता है।

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## टिप्पणियाँ


डिफ़ॉल्ट मान false है।

अगला उदाहरण दिखाता है कि निर्यातित PDF दस्तावेज़ में [Ink](../../../aspose.slides.ink/) तत्वों को कैसे छुपाया जाए:
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