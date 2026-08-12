---
title: EndRead()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस पढ़ने की प्रक्रिया के पूर्ण होने तक प्रतीक्षा करता है।
type: docs
weight: 261
url: /hi/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) मेथड


निर्दिष्ट असिंक्रोनस पढ़ने की प्रक्रिया के पूर्ण होने तक प्रतीक्षा करता है.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस पढ़ने की प्रक्रिया का प्रतिनिधित्व करता है |

### रिटर्न वैल्यू

पढ़ने की प्रक्रिया के दौरान पढ़े गए बाइट्स की संख्या, जिसे **asyncResult** द्वारा प्रतिनिधित्व किया गया है

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [NetworkStream](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)