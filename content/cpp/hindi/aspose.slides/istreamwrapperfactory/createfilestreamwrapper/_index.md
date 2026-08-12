---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट पथ और निर्माण मोड के साथ FileStream बनाता है।
type: docs
weight: 14
url: /hi/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) method


निर्दिष्ट पथ और निर्माण मोड के साथ FileStream बनाता है।

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | फ़ाइल नाम [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | फ़ाइल मोड [System::IO::FileMode](../../../system.io/filemode/) |

### रिटर्न मान

COM इंटरफ़ेस के लिए स्ट्रीम रैपर [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) method


निर्दिष्ट पथ, निर्माण मोड और पढ़ने/लिखने की अनुमति के साथ FileStream बनाता है।

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | फ़ाइल नाम [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | फ़ाइल मोड [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | फ़ाइल अभिगमन [System::IO::FileAccess](../../../system.io/fileaccess/) |

### रिटर्न मान

COM इंटरफ़ेस के लिए स्ट्रीम रैपर [IStreamWrapper](../../istreamwrapper/)

## संबंधित देखें

* एन्यूम [FileMode](../../../system.io/filemode/)
* एन्यूम [FileAccess](../../../system.io/fileaccess/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IStreamWrapper](../../istreamwrapper/)
* क्लास [String](../../../system/string/)
* क्लास [IStreamWrapperFactory](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)