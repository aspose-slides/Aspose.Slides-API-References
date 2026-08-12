---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो यह दर्शाता है कि पाठ को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 92
url: /hi/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() विधि

पाठ को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। जब **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर को अक्षम करें

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## देखें

* क्लास [HtmlOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)