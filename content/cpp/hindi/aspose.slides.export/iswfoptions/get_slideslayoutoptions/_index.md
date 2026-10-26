---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे ISlidesLayoutOptions प्राप्त करता है। यह प्रॉपर्टी प्रकार Aspose.Slides.Export.HandoutLayoutingOptions के ऑब्जेक्ट असाइन करने का समर्थन नहीं करती है।
type: docs
weight: 391
url: /hi/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() मेथड

एक प्रस्तुति निर्यात करते समय स्लाइड्स पृष्ठ पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/)। यह प्रॉपर्टी प्रकार **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)** के ऑब्जेक्ट असाइन करने का समर्थन नहीं करती है।

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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
* क्लास [ISwfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)