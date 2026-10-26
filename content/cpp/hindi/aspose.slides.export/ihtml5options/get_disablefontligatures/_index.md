---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो दर्शाता है कि पाठ लिगेचर का उपयोग किए बिना प्रस्तुत किया गया है या नहीं। जब true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 131
url: /hi/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() विधि

एक मान प्राप्त करता है जो दर्शाता है कि पाठ लिगेचर का उपयोग किए बिना प्रस्तुत किया गया है या नहीं। जब **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर निष्क्रिय करें

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## संबंधित देखें

* क्लास [IHtml5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)