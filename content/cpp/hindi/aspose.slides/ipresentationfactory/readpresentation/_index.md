---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक मौजूदा प्रस्तुति को ऐरे से पढ़ता है
type: docs
weight: 27
url: /hi/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) विधि

एक मौजूदा प्रस्तुति को ऐरे से पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़ने के लिए ऐरे |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) विधि

एक मौजूदा प्रस्तुति को ऐरे से अतिरिक्त लोड विकल्पों के साथ पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़ने के लिए ऐरे |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) विधि

एक मौजूदा प्रस्तुति को स्ट्रीम से पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | पढ़ने के लिये इनपुट स्ट्रीम |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) विधि

एक मौजूदा प्रस्तुति को स्ट्रीम से अतिरिक्त लोड विकल्पों के साथ पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | पढ़ने के लिये इनपुट स्ट्रीम |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## IPresentationFactory::ReadPresentation(System::String) विधि

एक मौजूदा प्रस्तुति को फ़ाइल से पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | फ़ाइल नाम |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) विधि

एक मौजूदा प्रस्तुति को स्ट्रीम से अतिरिक्त लोड विकल्पों के साथ पढ़ता है

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | फ़ाइल नाम |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | लोड विकल्प |

### रिटर्न मान

पढ़ी गई प्रस्तुति

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IPresentation](../../ipresentation/)
* क्लास [IPresentationFactory](../)
* क्लास [ILoadOptions](../../iloadoptions/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)