---
title: BeginSend()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक असिंक्रोनस भेजने ऑपरेशन शुरू करता है।
type: docs
weight: 495
url: /hi/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) मेथड

एक असिंक्रोनस भेजने ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा पढ़ने के लिए एक बफ़र। |
| offset | **int32_t** | निर्दिष्ट सरणी में बाइट्स में ऑफसेट। |
| size | **int32_t** | निर्दिष्ट सरणी में बाइट्स की संख्या, जो 'offset' पैरामीटर से शुरू होती है। |
| socketFlags | [SocketFlags](../../socketflags/) | भेजने का व्यवहार। |
| callback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन पूर्ण होने पर कॉल किया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस भेजने ऑपरेशन को विशिष्ट रूप से पहचानने के लिए प्रयोग होता है। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस भेजने ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* एनम [SocketFlags](../../socketflags/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [Socket](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)