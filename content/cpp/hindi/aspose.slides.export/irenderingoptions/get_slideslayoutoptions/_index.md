---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति को निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है ISlidesLayoutOptions.
type: docs
weight: 1
url: /hi/aspose.slides.export/irenderingoptions/get_slideslayoutoptions/
---
## IRenderingOptions::get_SlidesLayoutOptions() विधि

एक प्रस्तुति को निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, उसे प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/)।

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IRenderingOptions::get_SlidesLayoutOptions()=0
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);
slidesLayoutOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> handoutSlides = pres->GetThumbnails(options);
for (int32_t index = 0; index < handoutSlides->get_Length(); index++)
{
    auto handoutSlide = handoutSlides[index];
    handoutSlide->Save(System::String::Format(u"handout-{0}.png", index));
}
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [IRenderingOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)