---
title: set_DisableFontLigatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक मान सेट करता है जो दर्शाता है कि क्या टेक्स्ट को लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 53
url: /hi/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) मेथड


टेक्स्ट को बिना लिगेचर के रेंडर किया जाए या नहीं, यह दर्शाने के लिए एक मान सेट करता है। जब **true** सेट किया जाता है, तो लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है।

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर को निष्क्रिय करें

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## देखें

* क्लास [IRenderingOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)