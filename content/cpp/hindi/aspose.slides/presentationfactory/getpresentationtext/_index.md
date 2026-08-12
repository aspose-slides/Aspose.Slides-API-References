---
title: GetPresentationText()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्लाइडों से कच्चा पाठ प्राप्त करता है
type: docs
weight: 53
url: /hi/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) विधि

स्लाइडों से कच्चा पाठ प्राप्त करता है

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | इनपुट फ़ाइल |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |

### रिटर्न वैल्यू

[PresentationText](../../presentationtext/) का इंस्टेंस जिसमें SlideText एरे होता है जो कच्चा स्लाइड पाठ दर्शाता है

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) विधि

स्लाइडों से कच्चा पाठ प्राप्त करता है

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |

### रिटर्न वैल्यू

[PresentationText](../../presentationtext/) का इंस्टेंस जिसमें SlideText एरे होता है जो कच्चा स्लाइड पाठ दर्शाता है

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) विधि

स्लाइडों से कच्चा पाठ प्राप्त करता है

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | इनपुट स्ट्रीम |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | निकालने का मोड |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न वैल्यू

[PresentationText](../../presentationtext/) का इंस्टेंस जिसमें SlideText एरे होता है जो कच्चा स्लाइड पाठ दर्शाता है

## संबंधित देखें

* एनम [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPresentationText](../../ipresentationtext/)
* क्लास [String](../../../system/string/)
* क्लास [PresentationFactory](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [ILoadOptions](../../iloadoptions/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)