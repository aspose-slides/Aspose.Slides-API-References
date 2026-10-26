---
title: BeginResolve()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट होस्ट नाम का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाने के लिए एक असिंक्रोनस ऑपरेशन शुरू करता है।
type: docs
weight: 157
url: /hi/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) मेथड

निर्दिष्ट होस्ट नाम का उपयोग करके एक नया IPHostEntry-क्लास इंस्टेंस बनाने के लिए एक असिंक्रोनस ऑपरेशन शुरू करता है।

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | एक होस्ट नाम जो [IPHostEntry](../../iphostentry/) क्लास का नया उदाहरण बनाने के लिए उपयोग किया जाता है। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन पूर्ण होने पर कॉल किया जाने वाला एक कॉलबैक। |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोगकर्ता द्वारा प्रदान किया गया डेटा। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [Dns](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)