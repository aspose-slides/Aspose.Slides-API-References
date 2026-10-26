---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है ISlidesLayoutOptions.
type: docs
weight: 170
url: /hi/aspose.slides.export/itiffoptions/set_slideslayoutoptions/
---
## ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) विधि

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../../islideslayoutoptions/)।

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [ISlidesLayoutOptions](../../islideslayoutoptions/)
* वर्ग [ITiffOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)