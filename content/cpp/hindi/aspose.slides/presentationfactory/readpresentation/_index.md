---
title: ReadPresentation()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एरे से मौजूदा प्रस्तुति पढ़ता है
type: docs
weight: 40
url: /hi/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) विधि


एरे से मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़ने के लिए एरे |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) विधि


एरे से अतिरिक्त लोड विकल्पों के साथ मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़ने के लिए एरे |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) विधि


स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | पढ़ने के लिए इनपुट स्ट्रीम |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) विधि


स्ट्रीम से अतिरिक्त लोड विकल्पों के साथ मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | पढ़ने के लिए इनपुट स्ट्रीम |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## PresentationFactory::ReadPresentation(System::String) विधि


फ़ाइल से मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | फ़ाइल नाम |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) विधि


फ़ाइल से अतिरिक्त लोड विकल्पों के साथ मौजूदा प्रस्तुति पढ़ता है

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | फ़ाइल नाम |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IPresentation](../../ipresentation/)
* क्लास [PresentationFactory](../)
* क्लास [ILoadOptions](../../iloadoptions/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)