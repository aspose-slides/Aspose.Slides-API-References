---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: संसाधन पर डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु असिंक्रोनस ऑपरेशन शुरू करता है।
type: docs
weight: 469
url: /hi/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) विधि

संसाधन पर डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु असिंक्रोनस ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूर्ण होने पर कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोगकर्ता द्वारा प्रदान किया गया डेटा। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## सम्बंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* वर्ग [IAsyncResult](../../../system/iasyncresult/)
* वर्ग [Object](../../../system/object/)
* वर्ग [HttpWebRequest](../)
* नेमस्पेस [System::Net](../../)
* Library [Aspose.Slides](../../../)