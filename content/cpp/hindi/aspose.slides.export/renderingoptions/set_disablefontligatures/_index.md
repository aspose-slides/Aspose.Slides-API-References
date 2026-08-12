---
title: set_DisableFontLigatures()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक मान सेट करता है जो दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे true सेट किया जाता है, तो रेंडरित आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफॉल्ट रूप में, यह प्रॉपर्टी false पर सेट होती है।
type: docs
weight: 53
url: /hi/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) विधि


एक मान सेट करता है जो दर्शाता है कि क्या पाठ लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब **true** निर्धारित किया जाता है, तो रेंडरित आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // पाठ रेंडरिंग में लिगेचर को अक्षम करें

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## संबंधित देखें

* क्लास [RenderingOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)