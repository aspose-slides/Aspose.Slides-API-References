---
title: ToTiff()
second_title: Aspose.Slides for C++ API संदर्भ
description: इनपुट प्रस्तुति को TIFF फ़ॉर्मेट छवियों के सेट में बदलता है। यदि आउटपुट फ़ाइल नाम \"myPath/myFilename.tiff\" दिया गया हो, तो परिणाम \"myPath/myFilename_N.tiff\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।
type: docs
weight: 66
url: /hi/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) मेथड

Converts the input presentation to a set of TIFF format images.  

If the output file name is given as "myPath/myFilename.tiff", the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) मेथड

Converts the input presentation to TIFF format with custom options. If the output file name is given as "myPath/myFilename.tiff" and *multipage* **false**, the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number. Otherwise, if *multipage* **true**, the result will be a multi-page "myPath/myFilename.tiff" document.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | इनपुट प्रस्तुति। |
| outputFileName | [System::String](../../../system/string/) | आउटपुट फ़ाइल नाम। |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF सहेजने के विकल्प। |
| multipage | **bool** | निर्देशित करता है कि उत्पन्न TIFF दस्तावेज़ एक मल्टी-पेज होना चाहिए या नहीं। |
## टिप्पणियाँ

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [String](../../../system/string/)
* क्लास [Convert](../)
* क्लास [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)