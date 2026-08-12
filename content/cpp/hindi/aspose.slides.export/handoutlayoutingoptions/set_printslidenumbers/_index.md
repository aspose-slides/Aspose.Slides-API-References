---
title: set_PrintSlideNumbers()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्देशित करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या न किया जाए।
type: docs
weight: 40
url: /hi/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) मेथड


निर्दिष्ट करता है कि प्रदर्शित स्लाइड नंबरों को प्रिंट किया जाए या न हो।

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
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

## संबंधित

* क्लास [HandoutLayoutingOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)