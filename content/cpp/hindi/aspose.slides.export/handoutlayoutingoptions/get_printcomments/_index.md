---
title: get_PrintComments()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि स्लाइड पर टिप्पणियों को प्रदर्शित किया जाए या नहीं
type: docs
weight: 79
url: /hi/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const विधि


निर्दिष्ट करता है कि स्लाइड पर टिप्पणियों को दिखाना है या नहीं

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
```

## टिप्पणियाँ


डिफ़ॉल्ट मान **false** है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## देखें

* वर्ग [HandoutLayoutingOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)