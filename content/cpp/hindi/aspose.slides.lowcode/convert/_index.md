---
title: Convert
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेज़ेंटेशन को रूपांतरित करने के लिए नियत विधियों के एक समूह का प्रतिनिधित्व करता है।
type: docs
weight: 27
url: /hi/aspose.slides.lowcode/convert/
---
## रूपांतरण class

एक समूह विधियों का प्रतिनिधित्व करता है जो [Presentation](../../aspose.slides/presentation/) को रूपांतरित करने के लिए अभिप्रेत हैं।

```cpp
class Convert
```

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | पास किए गए आउटपुट पाथ एक्सटेंशन का उपयोग करके [Presentation](../../aspose.slides/presentation/) को रूपांतरित करता है ताकि आवश्यक एक्सपोर्ट फ़ॉर्मेट निर्धारित किया जा सके। |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | इनपुट प्रेज़ेंटेशन को JPEG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | इनपुट प्रेज़ेंटेशन को JPEG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | इनपुट प्रेज़ेंटेशन को JPEG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.jpeg\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.jpeg\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) को PDF में रूपांतरित करता है। |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/) को PDF में रूपांतरित करता है। |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) को PDF में रूपांतरित करता है। |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/) को PDF में रूपांतरित करता है। |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | इनपुट प्रेज़ेंटेशन को PNG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | इनपुट प्रेज़ेंटेशन को PNG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | इनपुट प्रेज़ेंटेशन को PNG फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.png\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.png\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/) को SVG में रूपांतरित करता है। |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/) को SVG में रूपांतरित करता है। |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/) को SVG में रूपांतरित करता है। |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/) को SVG में रूपांतरित करता है। |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/) को SVG में रूपांतरित करता है। |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | इनपुट प्रेज़ेंटेशन को TIFF फ़ॉर्मेट इमेजेस के सेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.tiff\" के रूप में दिया जाता है, तो परिणाम \"myPath/myFilename_N.tiff\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | इनपुट प्रेज़ेंटेशन को कस्टम विकल्पों के साथ TIFF फ़ॉर्मेट में रूपांतरित करता है।\n\nयदि आउटपुट फ़ाइल नाम \"myPath/myFilename.tiff\" के रूप में दिया जाता है और *multipage* **false** है, तो परिणाम \"myPath/myFilename_N.tiff\" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। अन्यथा, यदि *multipage* **true** है, तो परिणाम एक मल्टी-पेज \"myPath/myFilename.tiff\" दस्तावेज़ होगा। |

## टाइपडिफ

| टाइपडिफ | वर्णन |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | एक कॉलबैक जो प्रत्येक [Slide](../../aspose.slides/slide/) के लिये कॉल किया जाएगा, जहाँ अपेक्षित है कि आउटपुट पाथ लौटाया जाए। |

## टिप्पणियाँ

```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## See Also

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)