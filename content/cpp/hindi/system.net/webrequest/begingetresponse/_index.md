---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API संदर्भ
description: संसाधन के लिए एक असिंक्रोनस अनुरोध शुरू करता है।
type: docs
weight: 274
url: /hi/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) मेथड

संसाधन के लिए एक असिंक्रोनस अनुरोध शुरू करता है।

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### आर्गुमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जिसे ऑपरेशन पूर्ण होने पर बुलाया जाता है। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया जाता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [WebRequest](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)