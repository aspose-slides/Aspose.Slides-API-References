---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग जिसका होस्टनाम या IP पता हो, उसका उपयोग करके एक नया IPHostEntry-क्लास इंस्टेंस बनाने के लिए असिंक्रोनस ऑपरेशन प्रारंभ करता है।
type: docs
weight: 105
url: /hi/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) मेथड

निर्दिष्ट स्ट्रिंग का उपयोग करके जिसमें होस्ट नाम या IP पता हो, एक नया IPHostEntry-क्लास इंस्टेंस बनाने के लिए असिंक्रोनस ऑपरेशन प्रारंभ करता है।

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | एक स्ट्रिंग जिसमें होस्टनाम या IP पता हो। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | जब ऑपरेशन पूरा हो जाए तो कॉल किया जाने वाला कॉलबैक। |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया गया उपयोगकर्ता-द्वारा प्रदान किया गया डेटा। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) मेथड

निर्दिष्ट IP पते का उपयोग करके एक नया IPHostEntry-क्लास इंस्टेंस बनाने के लिए असिंक्रोनस ऑपरेशन प्रारंभ करता है।

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP पता। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | जब ऑपरेशन पूरा हो जाए तो कॉल किया जाने वाला कॉलबैक। |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | प्रत्येक असिंक्रोनस ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया गया उपयोगकर्ता-द्वारा प्रदान किया गया डेटा। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारम्भ किए गए असिंक्रोनस ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ़ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [Dns](../)
* क्लास [IPAddress](../../ipaddress/)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)