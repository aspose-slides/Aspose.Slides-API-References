---
title: get_DisableFontLigatures()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक मान प्राप्त करता है जो यह दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह गुण false पर सेट होता है।
type: docs
weight: 326
url: /hi/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISSVGOptions::get_DisableFontLigatures() मेथड

एक मान प्राप्त करता है जो यह दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह गुण **false** पर सेट होता है।

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर को निष्क्रिय करें

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## देखें भी

* क्लास [ISVGOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)