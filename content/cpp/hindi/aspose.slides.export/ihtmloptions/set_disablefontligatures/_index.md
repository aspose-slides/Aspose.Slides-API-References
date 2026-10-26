---
title: set_DisableFontLigatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सेट करता है एक मान जो यह दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब true सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 196
url: /hi/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) मेथड

सेट करता है एक मान जो यह दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब **true** सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर निष्क्रिय करें

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## देखें

* क्लास [IHtmlOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)