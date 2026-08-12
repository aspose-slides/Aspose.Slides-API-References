---
title: get_PrintSlideNumbers()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबर मुद्रित किए जाएँ या नहीं।
type: docs
weight: 27
url: /hi/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const विधि


निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबर मुद्रित किए जाएँ या नहीं।

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## टिप्पणियाँ


डिफ़ॉल्ट मान **true** है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## संबंधित देखें

* क्लास [HandoutLayoutingOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)