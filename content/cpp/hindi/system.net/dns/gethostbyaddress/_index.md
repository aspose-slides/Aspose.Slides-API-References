---
title: GetHostByAddress()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट IP पते के स्ट्रिंग प्रतिनिधित्व का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाता है।
type: docs
weight: 14
url: /hi/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) मेथड


निर्दिष्ट IP पते के स्ट्रिंग प्रतिनिधित्व का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP पते का स्ट्रिंग प्रतिनिधित्व। |

### Return Value

एक नया IPHostEntry-class इंस्टेंस।

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) मेथड


निर्दिष्ट IP पते का उपयोग करके एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP पता। |

### Return Value

एक नया IPHostEntry-class इंस्टेंस।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)