---
title: set_SlidesLayoutOptions()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है ISlidesLayoutOptions. यह प्रॉपर्टी प्रकार Aspose.Slides.Export.HandoutLayoutingOptions की वस्तुओं को असाइन करने का समर्थन नहीं करती है।
type: docs
weight: 404
url: /hi/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) विधि

स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है जब प्रस्तुति [ISlidesLayoutOptions](../../islideslayoutoptions/) को निर्यात किया जाता है। यह प्रॉपर्टी प्रकार **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** की वस्तुओं को असाइन करने का समर्थन नहीं करती है।

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## टिप्पणियाँ

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

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [ISwfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)