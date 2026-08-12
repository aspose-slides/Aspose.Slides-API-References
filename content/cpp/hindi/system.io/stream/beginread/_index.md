---
title: BeginRead()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक असिंक्रोनस पढ़ने का ऑपरेशन प्रारंभ करता है।
type: docs
weight: 157
url: /hi/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) method


एक असिंक्रोनस पढ़ने का ऑपरेशन प्रारंभ करता है।

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | पढ़ने के लिए एक बफ़र |
| offset | int | **buffer** में 0-आधारित ऑफ़सेट जो पढ़े गए डेटा को लिखना शुरू करने की स्थिति दर्शाता है |
| count | int | पढ़ने के लिए बाइट्स की संख्या |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूरा होने पर कॉल किया जाने वाला कॉलबैक |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस पढ़ने के ऑपरेशन को अद्वितीय रूप से पहचानने के लिए उपयोगकर्ता द्वारा प्रदान किया गया डेटा |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस पढ़ने के ऑपरेशन का प्रतिनिधित्व करता है

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [Stream](../)
* नामस्थान [System::IO](../../)
* लाइब्रेरी [Aspose.Slides](../../../)