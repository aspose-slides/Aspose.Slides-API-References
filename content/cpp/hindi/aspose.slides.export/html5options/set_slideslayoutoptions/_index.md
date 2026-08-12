---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन को निर्यात करते समय पृष्ठ पर स्लाइड्स रखने के मोड को सेट करता है ISlidesLayoutOptions.
type: docs
weight: 170
url: /hi/aspose.slides.export/html5options/set_slideslayoutoptions/
---
## Html5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) विधि

प्रस्तुति निर्यात करते समय स्लाइड को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::Html5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)