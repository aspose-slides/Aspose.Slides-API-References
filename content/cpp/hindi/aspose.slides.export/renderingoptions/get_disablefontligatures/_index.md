---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मान प्राप्त करता है जो यह दर्शाता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। जब इसे true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी का मान false पर सेट होता है।
type: docs
weight: 40
url: /hi/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() मेथड


टेक्स्ट को बिना लिगेचर के रेंडर किया जाए, यह दर्शाने वाला मान प्राप्त करता है। जब **true** सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी का मान **false** होता है।

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## टिप्पणियाँ


उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // टेक्स्ट रेंडरिंग में लिगेचर निष्क्रिय करें

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