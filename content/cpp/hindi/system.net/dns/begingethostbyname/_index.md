---
title: BeginGetHostByName()
second_title: Aspose.Slides for C++ API रेफरेंस
description: निर्दिष्ट होस्ट नाम का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाने के लिए एक असिंक्रोनस ऑपरेशन शुरू करता है।
type: docs
weight: 53
url: /hi/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) विधि

निर्दिष्ट होस्ट नाम का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाने के लिए एक असिंक्रोनस ऑपरेशन शुरू करता है।

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | एक होस्ट नाम। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | ऑपरेशन के पूर्ण होने पर बुलाए जाने वाला एक कॉलबैक। |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोगकर्ता द्वारा प्रदान किया गया डेटा। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)