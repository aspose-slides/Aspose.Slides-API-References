---
title: GetPresentationInfo()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: फ़ाइल से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को इससे जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) विधि

फ़ाइल से नई [PresentationInfo](../../presentationinfo/) ऑब्जेक्ट बनाता है और प्रस्तुति को इससे जोड़ता है।

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) फ़ाइल। |

### वापसी मान

[Presentation](../../presentation/) जानकारी प्रस्तुति से बंधी हुई है।

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) विधि

स्ट्रीम से नई [PresentationInfo](../../presentationinfo/) ऑब्जेक्ट बनाता है और प्रस्तुति को इससे जोड़ता है। निर्दिष्ट स्ट्रीम में प्रस्तुति के बारे में जानकारी प्राप्त करता है।

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) स्ट्रीम। |

### वापसी मान

[Presentation](../../presentation/) जानकारी प्रस्तुति से बंधी हुई है।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPresentationInfo](../../ipresentationinfo/)
* क्लास [String](../../../system/string/)
* क्लास [PresentationFactory](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)