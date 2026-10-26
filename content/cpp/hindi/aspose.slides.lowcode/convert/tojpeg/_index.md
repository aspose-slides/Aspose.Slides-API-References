---
title: ToJpeg()
second_title: Aspose.Slides for C++ API संदर्भ
description: इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" दिया गया है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड नंबर है।
type: docs
weight: 40
url: /hi/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) विधि


इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" दिया गया है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड नंबर है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
## टिप्पणियाँ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) विधि


इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" दिया गया है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड नंबर है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | प्रत्येक उत्पन्न छवि का आकार। |
## टिप्पणियाँ




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) विधि


इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" दिया गया है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड नंबर है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
| scale | **float** | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू किया गया स्केलिंग कारक। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
## टिप्पणियाँ




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [String](../../../system/string/)
* क्लास [Convert](../)
* क्लास [Size](../../../system.drawing/size/)
* क्लास [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* नामस्थान [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)