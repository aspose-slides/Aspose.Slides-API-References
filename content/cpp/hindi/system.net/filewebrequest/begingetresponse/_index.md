---
title: BeginGetResponse()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संसाधन के लिए एक असिंक्रोनस अनुरोध शुरू करता है।
type: docs
weight: 170
url: /hi/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) विधि

संसाधन के लिए एक असिंक्रोनस अनुरोध शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन के पूर्ण होने पर कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोगकर्ता द्वारा प्रदान किया गया डेटा। |

### रिटर्न वैल्यू

[IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [FileWebRequest](../)
* नेमस्पेस [System::Net](../../)
* Library [Aspose.Slides](../../../)