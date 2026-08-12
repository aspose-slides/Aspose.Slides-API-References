---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो दर्शाता है कि क्या पाठ को लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब true पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 131
url: /hi/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() विधि


लेखक एक मान प्राप्त करता है जो दर्शाता है कि क्या पाठ को लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को अक्षम करें

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## संबंधित देखें

* क्लास [Html5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)