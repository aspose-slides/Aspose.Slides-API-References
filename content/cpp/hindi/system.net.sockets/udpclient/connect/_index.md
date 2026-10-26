---
title: Connect()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट होस्ट पर निर्दिष्ट पोर्ट तक एक कनेक्शन स्थापित करता है।
type: docs
weight: 66
url: /hi/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) विधि

निर्दिष्ट होस्ट पर निर्दिष्ट पोर्ट के साथ एक कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | जिस रिमोट DNS होस्ट से आप कनेक्ट होना चाहते हैं, उसका नाम। |
| port | **int32_t** | जिस स्थानीय पोर्ट नंबर से आप संचार करना चाहते हैं। |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) विधि

निर्दिष्ट पोर्ट पर निर्दिष्ट पते पर स्थित होस्ट के साथ एक कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | दूरस्थ होस्ट का [IPAddress](../../../system.net/ipaddress/) जिससे डेटा भेजा जाना है। |
| port | **int32_t** | जिस स्थानीय पोर्ट नंबर से आप संचार करना चाहते हैं। |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) विधि

दूरस्थ एंडपॉइंट पर एक कनेक्शन स्थापित करता है।

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | UDP कनेक्शन को जिसे आप बाइंड करेंगे, वह एंडपॉइंट। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [UdpClient](../)
* क्लास [IPAddress](../../../system.net/ipaddress/)
* क्लास [IPEndPoint](../../../system.net/ipendpoint/)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)