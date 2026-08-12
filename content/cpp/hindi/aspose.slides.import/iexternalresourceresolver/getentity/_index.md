---
title: GetEntity()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक URI को वास्तविक संसाधन वाला ऑब्जेक्ट से मैप करता है।
type: docs
weight: 14
url: /hi/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) विधि

एक URI को वास्तविक संसाधन युक्त ऑब्जेक्ट से मैप करता है।

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | ऑब्जेक्ट के लिए पूर्ण URI। |

### रिटर्न वैल्यू

यदि संसाधन को स्ट्रीम नहीं किया जा सकता है तो एक [System::IO::Stream](../../../system.io/stream/) ऑब्जेक्ट या null।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* क्लास [IExternalResourceResolver](../)
* नेमस्पेस [Aspose::Slides::Import](../../)
* लाइब्रेरी [Aspose.Slides](../../../)