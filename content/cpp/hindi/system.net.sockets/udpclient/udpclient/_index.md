---
title: UdpClient()
second_title: Aspose.Slides for C++ API संदर्भ
description: UdpClient क्लास का नया उदाहरण आरम्भ करता है।
type: docs
weight: 27
url: /hi/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण प्रारम्भ करता है।

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण प्रारम्भ करता है।

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | सॉकेट की एड्रेसिंग स्कीम निर्दिष्ट करने वाला मान। |

## UdpClient::UdpClient(int32_t) कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण प्रारम्भ करता है।

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| port | **int32_t** | वह स्थानीय पोर्ट नंबर जिससे आप संचार करना चाहते हैं। |

## UdpClient::UdpClient(int32_t, AddressFamily) कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण प्रारम्भ करता है।

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| port | **int32_t** | वह स्थानीय पोर्ट नंबर जिससे आप संचार करना चाहते हैं। |
| family | [AddressFamily](../../addressfamily/) | सॉकेट की एड्रेसिंग स्कीम निर्दिष्ट करने वाला मान। |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण प्रारम्भ करता है। param local EP वह स्थानीय एंडपॉइंट जिससे आप UDP कनेक्शन बाइंड करते हैं।

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) कन्स्ट्रक्टर

एक नया [UdpClient](../) क्लास का उदाहरण बनाता है और निर्दिष्ट पोर्ट पर निर्दिष्ट रिमोट होस्ट से कनेक्ट करता है।

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | वह रिमोट DNS होस्ट का नाम जिससे आप कनेक्ट होना चाहते हैं। |
| port | **int32_t** | वह स्थानीय पोर्ट नंबर जिससे आप संचार करना चाहते हैं। |

## देखें

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)