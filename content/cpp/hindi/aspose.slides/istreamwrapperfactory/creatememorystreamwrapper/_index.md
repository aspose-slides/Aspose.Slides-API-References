---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: MemoryStream रैपर बनाता है।
type: docs
weight: 1
url: /hi/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() विधि

MemoryStream रैपर बनाता है।

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### रिटर्न वैल्यू

COM इंटरफ़ेस [IStreamWrapper](../../istreamwrapper/) के लिए स्ट्रीम रैपर

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट बाइट एरे पर आधारित MemoryStream रैपर बनाता है।

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे **uint8_t**[] |

### रिटर्न वैल्यू

COM इंटरफ़ेस [IStreamWrapper](../../istreamwrapper/) के लिए स्ट्रीम रैपर

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)