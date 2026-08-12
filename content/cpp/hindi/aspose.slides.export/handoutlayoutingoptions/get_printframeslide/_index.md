---
title: get_PrintFrameSlide()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रदर्शित स्लाइडों के चारों ओर फ़्रेम खींचे जाएँ या नहीं।
type: docs
weight: 53
url: /hi/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const मेथड

निर्दिष्ट करता है कि प्रदर्शित स्लाइडों के चारों ओर फ़्रेम खींचे जाएँ या नहीं।

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## टिप्पणी

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
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)