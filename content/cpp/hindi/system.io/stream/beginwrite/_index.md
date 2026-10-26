---
title: BeginWrite()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है।
type: docs
weight: 170
url: /hi/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) विधि


एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है।

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | एक बफ़र जिसमें लिखे जाने वाले डेटा होते हैं |
| offset | int | **buffer** में 0-आधारित ऑफ़सेट जो उस स्थिति को दर्शाता है जहाँ से लिखने के लिए डेटा शुरू होता है |
| count | int | लिखने के लिए बाइट्स की संख्या |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूर्ण होने पर कॉल किया जाने वाला कॉलबैक |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस लिखने वाले ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया गया उपयोगकर्ता-प्रदान किया गया डेटा |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस लिखने वाले ऑपरेशन का प्रतिनिधित्व करता है

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [Stream](../)
* नेमस्पेस [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)