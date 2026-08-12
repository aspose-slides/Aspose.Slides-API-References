---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान सेट करता है जो दर्शाता है कि टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 339
url: /hi/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) विधि

टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाए यह दर्शाने वाला मान सेट करता है। जब इसे **true** पर सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को अक्षम करें

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## संबंधित देखें

* क्लास [ISVGOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)