---
title: ToPng()
second_title: Aspose.Slides for C++ API संदर्भ
description: इनपुट प्रस्तुति को PNG स्वरूप की छवियों के सेट में बदलता है। यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" दिया गया है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।
type: docs
weight: 53
url: /hi/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) method


इनपुट प्रस्तुति को PNG स्वरूप की छवियों के सेट में बदलता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" दिया गया है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method


इनपुट प्रस्तुति को PNG स्वरूप की छवियों के सेट में बदलता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" दिया गया है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | प्रत्येक उत्पन्न छवि का आकार। |
## टिप्पणी 




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method


इनपुट प्रस्तुति को PNG स्वरूप की छवियों के सेट में बदलता है। 

यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" दिया गया है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
| scale | **float** | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फ़ैक्टर। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
## टिप्पणी 




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)