---
title: set_DisableFontLigatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक मान सेट करता है जो दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 105
url: /hi/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) method


एक मान सेट करता है जो दर्शाता है कि क्या टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को अक्षम करें

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## संबंधित देखें

* क्लास [HtmlOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)