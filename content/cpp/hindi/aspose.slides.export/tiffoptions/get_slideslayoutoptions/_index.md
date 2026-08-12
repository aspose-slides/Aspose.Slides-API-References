---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है ISlidesLayoutOptions.
type: docs
weight: 170
url: /hi/aspose.slides.export/tiffoptions/get_slideslayoutoptions/
---
## TiffOptions::get_SlidesLayoutOptions() विधि

एक प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::TiffOptions::get_SlidesLayoutOptions() override
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [TiffOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)