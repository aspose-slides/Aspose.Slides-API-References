---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग (जिसमें होस्ट नाम या IP पता शामिल है) का उपयोग करके एक नया IPHostEntry-क्लास इंस्टेंस बनाने के लिए असिंक्रोनस ऑपरेशन शुरू करता है।
type: docs
weight: 131
url: /hi/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस ऑपरेशन शुरू करता है जो निर्दिष्ट स्ट्रिंग (जिसमें होस्टनाम या IP पता हो) का उपयोग करके एक नया IPHostEntry-क्लास इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | एक स्ट्रिंग जो होस्टनाम या IP पते को शामिल करती है। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जिसे ऑपरेशन के पूरा होने पर बुलाया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो आरंभ किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [Dns](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)