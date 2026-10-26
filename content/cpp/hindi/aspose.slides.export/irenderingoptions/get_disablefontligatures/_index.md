---
title: get_DisableFontLigatures()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऐसा मान प्राप्त करता है जो यह दर्शाता है कि क्या टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है। जब इसे true पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी को false पर सेट किया गया है।
type: docs
weight: 40
url: /hi/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() विधि


ऐसा मान प्राप्त करता है जो यह दर्शाता है कि क्या टेक्स्ट लिगेचर का उपयोग किए बिना प्रदर्शित किया जाता है। जब **true** पर सेट किया जाता है, तो लिगेचर आउटपुट में अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, इस प्रॉपर्टी को **false** पर सेट किया गया है।

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## टिप्पणियाँ


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

## संबंधित देखें

* क्लास [IRenderingOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)