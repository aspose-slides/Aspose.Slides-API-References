---
title: set_PrintComments()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट करता है कि स्लाइड पर टिप्पणियाँ प्रदर्शित करनी हैं या नहीं
type: docs
weight: 92
url: /hi/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) मेथड

निर्दिष्ट करता है कि स्लाइड पर टिप्पणियाँ प्रदर्शित करनी हैं या नहीं

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
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

* क्लास [HandoutLayoutingOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)