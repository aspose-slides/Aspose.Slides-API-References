---
title: BeginWrite()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है।
type: docs
weight: 443
url: /hi/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा लिखने के लिए बाइट एरे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट में ऑफ़सेट। |
| count | **int32_t** | लिखने के लिए बाइट की संख्या। |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूरा होने पर बुलाया जाने वाला कॉलबैक। |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस लिखने के ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किए जाने वाले उपयोगकर्ता द्वारा प्रदान किया गया डेटा। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस लिखने के ऑपरेशन का प्रतिनिधित्व करता है।

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [SslStream](../)
* नेमस्पेस [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)