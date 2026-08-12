---
title: EndRead()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूरी होने तक प्रतीक्षा करता है।
type: docs
weight: 183
url: /hi/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) method

निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूरी होने तक प्रतीक्षा करता है।

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस रीड ऑपरेशन का प्रतिनिधित्व करता है |

### वापसी मान

बाइट्स की संख्या जो **asyncResult** द्वारा प्रतिनिधित्व किए गए रीड ऑपरेशन के दौरान पढ़ी गई

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Stream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)