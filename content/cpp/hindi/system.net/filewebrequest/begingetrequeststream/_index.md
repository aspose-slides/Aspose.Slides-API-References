---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: संसाधन में डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु असिंक्रोनस ऑपरेशन को प्रारंभ करता है।
type: docs
weight: 144
url: /hi/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) विधि

संसाधन में डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु एक असिंक्रोनस ऑपरेशन प्रारंभ करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन के पूरा होने पर कॉल किया जाने वाला callback। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस ऑपरेशन को अद्वितीय रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ की गई असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)