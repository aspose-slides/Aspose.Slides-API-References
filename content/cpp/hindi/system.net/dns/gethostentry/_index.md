---
title: GetHostEntry()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग का उपयोग करके, जिसमें होस्ट नाम या IP पता होता है, एक नया IPHostEntry-class इंस्टेंस बनाता है।
type: docs
weight: 79
url: /hi/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) method

निर्दिष्ट स्ट्रिंग का उपयोग करके, जिसमें होस्ट नाम या IP पता होता है, एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | वह स्ट्रिंग जो होस्टनाम या IP पता समाहित करती है। |

### Return Value

एक नया निर्मित IPHostEntry-class इंस्टेंस।

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) method

निर्दिष्ट IP पते का उपयोग करके, एक नया IPHostEntry-class इंस्टेंस बनाता है।

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP पता। |

### Return Value

एक नया निर्मित IPHostEntry-class इंस्टेंस।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPHostEntry](../../iphostentry/)
* क्लास [String](../../../system/string/)
* क्लास [Dns](../)
* क्लास [IPAddress](../../ipaddress/)
* नेमस्पेस [System::Net](../../)
* Library [Aspose.Slides](../../../)