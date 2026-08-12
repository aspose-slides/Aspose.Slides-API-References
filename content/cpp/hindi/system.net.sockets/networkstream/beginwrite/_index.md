---
title: BeginWrite()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: एक असिंक्रोनस लिखने के ऑपरेशन को शुरू करता है।
type: docs
weight: 274
url: /hi/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) मेथड

एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | लिखे जाने वाले डेटा युक्त एक बफ़र। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | लिखने के लिए बाइट्स की संख्या। |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन के पूरा होने पर कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस लिखने वाले ऑपरेशन को अनन्य रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस लिखने के ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [NetworkStream](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)