---
title: GetPresentationText()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: स्लाइड्स से कच्चा टेक्स्ट प्राप्त करता है
type: docs
weight: 40
url: /hi/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) विधि

स्लाइड्स से कच्चा टेक्स्ट प्राप्त करता है

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | इनपुट फ़ाइल |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |

### रिटर्न मान

इंस्टेंस [PresentationText](../../presentationtext/) जिसमें SlideText एरे है जो कच्चा स्लाइड्स टेक्स्ट दर्शाता है

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) विधि

स्लाइड्स से कच्चा टेक्स्ट प्राप्त करता है

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |

### रिटर्न मान

इंस्टेंस [PresentationText](../../presentationtext/) जिसमें SlideText एरे है जो कच्चा स्लाइड्स टेक्स्ट दर्शाता है

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) विधि

स्लाइड्स से कच्चा टेक्स्ट प्राप्त करता है

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

इंस्टेंस [PresentationText](../../presentationtext/) जिसमें SlideText एरे है जो कच्चा स्लाइड्स टेक्स्ट दर्शाता है

## संबंधित देखें

* एनम [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPresentationText](../../ipresentationtext/)
* क्लास [String](../../../system/string/)
* क्लास [IPresentationFactory](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [ILoadOptions](../../iloadoptions/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)