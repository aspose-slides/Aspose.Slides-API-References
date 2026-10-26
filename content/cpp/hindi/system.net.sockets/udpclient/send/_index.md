---
title: Send()
second_title: Aspose.Slides for C++ API संदर्भ
description: रिमोट एंड पॉइंट पर स्थित होस्ट को एक UDP डेटाग्राम भेजता है।
type: docs
weight: 79
url: /hi/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) विधि

एक UDP डेटाग्राम को रिमोट एन्ड-पॉइंट पर स्थित होस्ट को भेजता है।

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### आर्ग्यूमेंट्स

| पैरामिटर | प्रकार | विवरण |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए [Byte](../../../system/byte/) प्रकार का एक एरे |
| bytes | **int32_t** | डेटाग्राम में बाइट्स की संख्या |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | वह [IPEndPoint](../../../system.net/ipendpoint/) जो होस्ट और पोर्ट को दर्शाता है, जिस पर डेटाग्राम भेजना है |

### रिटर्न मान

भेजे गए बाइट्स की संख्या।

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) विधि

निर्दिष्ट रिमोट होस्ट पर निर्दिष्ट पोर्ट को एक UDP डेटाग्राम भेजता है।

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### आर्ग्यूमेंट्स

| पैरामिटर | प्रकार | विवरण |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए [Byte](../../../system/byte/) प्रकार का एक एरे |
| bytes | **int32_t** | डेटाग्राम में बाइट्स की संख्या |
| hostname | [String](../../../system/string/) | रिमोट होस्ट का नाम |
| port | **int32_t** | रिमोट पोर्ट नंबर |

### रिटर्न मान

भेजे गए बाइट्स की संख्या।

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) विधि

एक रिमोट होस्ट को UDP डेटाग्राम भेजता है।

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### आर्ग्यूमेंट्स

| पैरामिटर | प्रकार | विवरण |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | भेजने के लिए [Byte](../../../system/byte/) प्रकार का एक एरे |
| bytes | **int32_t** | डेटाग्राम में बाइट्स की संख्या |

### रिटर्न मान

भेजे गए बाइट्स की संख्या।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPEndPoint](../../../system.net/ipendpoint/)
* क्लास [UdpClient](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)