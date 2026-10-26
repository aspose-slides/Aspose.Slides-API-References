---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: संसाधन पर डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु एक असिंक्रोनस ऑपरेशन शुरू करता है।
type: docs
weight: 300
url: /hi/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method

संसाधन पर डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु एक असिंक्रोनस ऑपरेशन शुरू करता है।

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूर्ण होने पर कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट पहचानता है। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [WebRequest](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)