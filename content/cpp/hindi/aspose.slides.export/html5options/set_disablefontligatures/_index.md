---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान सेट करता है जो यह दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब true सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप में, यह प्रॉपर्टी false पर सेट रहती है।
type: docs
weight: 144
url: /hi/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) मेथड

एक मान सेट करता है जो यह दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब **true** सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट रहती है।

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को निष्क्रिय करें

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## देखें

* क्लास [Html5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)