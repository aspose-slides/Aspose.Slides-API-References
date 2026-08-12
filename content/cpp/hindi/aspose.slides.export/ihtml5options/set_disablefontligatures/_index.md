---
title: set_DisableFontLigatures()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक मान सेट करता है जो दर्शाता है कि क्या पाठ को लिगेचर का उपयोग किए बिना रेंडर किया गया है। जब true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 144
url: /hi/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) विधि

एक मान सेट करता है जो दर्शाता है कि क्या पाठ को लिगेचर का उपयोग किए बिना रेंडर किया गया है। जब **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर निष्क्रिय करें

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## देखें

* क्लास [IHtml5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)