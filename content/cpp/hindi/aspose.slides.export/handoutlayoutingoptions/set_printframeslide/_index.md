---
title: set_PrintFrameSlide()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के आसपास फ्रेम खींचे जाएँ या नहीं।
type: docs
weight: 66
url: /hi/aspose.slides.export/handoutlayoutingoptions/set_printframeslide/
---
## HandoutLayoutingOptions::set_PrintFrameSlide(bool) मेथड


निर्दिष्ट करता है कि प्रदर्शित स्लाइड्स के आसपास फ्रेम ड्रॉ किए जाएँ या नहीं।

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintFrameSlide(bool value)
```

## टिप्पणियाँ


डिफ़ॉल्ट मान **true** है।

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## संबंधित देखें

* क्लास [HandoutLayoutingOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)