---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides का C++ API संदर्भ
description: जब प्रस्तुति निर्यात की जाती है, तब पृष्ठ पर स्लाइड्स को रखने के मोड को सेट करता है ISlidesLayoutOptions. यह प्रॉपर्टी प्रकार HandoutLayoutingOptions के ऑब्जेक्ट्स को असाइन करने का समर्थन नहीं करती
type: docs
weight: 404
url: /hi/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../../islideslayoutoptions/). यह प्रॉपर्टी प्रकार के ऑब्जेक्ट्स को असाइन करने का समर्थन नहीं करती [HandoutLayoutingOptions](../../handoutlayoutingoptions/)

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [SwfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)