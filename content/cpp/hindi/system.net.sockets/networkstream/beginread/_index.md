---
title: BeginRead()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक असिंक्रोनस पढ़ने का ऑपरेशन शुरू करता है।
type: docs
weight: 248
url: /hi/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस पढ़ने का ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे जहाँ पढ़े गए बाइट्स लिखे जाएंगे। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | पढ़ने के लिए बाइट्स की संख्या। |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन के पूरा होने पर कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस पढ़ने के ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस पढ़ने के ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [NetworkStream](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)