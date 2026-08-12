---
title: set_DisableFontLigatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक मान सेट करता है जो यह दर्शाता है कि पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 339
url: /hi/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) विधि


लिगेचर का उपयोग किए बिना पाठ को रेंडर किया जाता है या नहीं, यह दर्शाने वाला मान सेट करता है। जब **true** सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
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

## देखें

* क्लास [SVGOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)