---
title: set_Handout()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि पृष्ठ पर कितनी स्लाइड्स और किस क्रम में HandoutType रखा जाएगा।
type: docs
weight: 14
url: /hi/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) विधि


पृष्ठ पर कितनी स्लाइड्स और किस क्रम में रखी जाएँगी [HandoutType](../../handouttype/)।

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## टिप्पणियाँ


डिफ़ॉल्ट मान है **[HandoutType::Handouts6Horizontal](../../handouttype/)**। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## देखें

* Enum [HandoutType](../../handouttype/)
* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)