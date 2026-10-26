---
title: get_Handout()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट करता है कि पृष्ठ HandoutType पर कितनी स्लाइड्स और किस क्रम में रखी जाएँगी।
type: docs
weight: 1
url: /hi/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const विधि


निर्दिष्ट करता है कि पृष्ठ [HandoutType](../../handouttype/) पर कितनी स्लाइड्स और किस क्रम में रखी जाएँगी।

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## टिप्पणियाँ


डिफॉल्ट मान है **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

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

## संबंधित देखें

* Enum [HandoutType](../../handouttype/)
* क्लास [HandoutLayoutingOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)