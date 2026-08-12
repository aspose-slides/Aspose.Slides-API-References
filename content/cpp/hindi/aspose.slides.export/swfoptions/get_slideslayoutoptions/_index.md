---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है ISlidesLayoutOptions। यह प्रॉपर्टी HandoutLayoutingOptions प्रकार की वस्तुओं को असाइन करने का समर्थन नहीं करती है।
type: docs
weight: 391
url: /hi/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() विधि


प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/)। यह संपत्ति प्रकार [HandoutLayoutingOptions](../../handoutlayoutingoptions/) की वस्तुओं को असाइन करने का समर्थन नहीं करती है।

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
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

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [SwfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)