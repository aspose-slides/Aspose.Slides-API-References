---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो यह दर्शाता है कि टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब true पर सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी को false पर सेट किया गया है।
type: docs
weight: 183
url: /hi/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() विधि


एक मान प्राप्त करता है जो यह दर्शाता है कि टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब **true** पर सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी को **false** पर सेट किया गया है।

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
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

* वर्ग [IHtmlOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)