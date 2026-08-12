---
title: GetPresentationInfo()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट फ़ाइल में प्रस्तुति की जानकारी प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) विधि


निर्दिष्ट फ़ाइल में प्रस्तुति की जानकारी प्राप्त करता है।

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) फ़ाइल। |

### वापसी मान

[Presentation](../../presentation/) जानकारी

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) विधि


निर्दिष्ट स्ट्रीम में प्रस्तुति की जानकारी प्राप्त करता है।

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) स्ट्रीम। |

### वापसी मान

[Presentation](../../presentation/) जानकारी।

## साथ में देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)