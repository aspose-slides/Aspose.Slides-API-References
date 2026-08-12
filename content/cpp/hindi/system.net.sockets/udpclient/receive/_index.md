---
title: Receive()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक सर्वर द्वारा भेजे गए डेटाग्राम को लौटाता है।
type: docs
weight: 92
url: /hi/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) मेथड

एक सर्वर द्वारा भेजा गया डेटाग्राम लौटाता है।

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | एक [IPEndPoint](../../../system.net/ipendpoint/) जो उस रिमोट होस्ट का प्रतिनिधित्व करता है जिससे डेटा भेजा गया था। |

### रिटर्न वैल्यू

एक बाइट ऐरे जहाँ प्राप्त डेटा असाइन किया जाएगा।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPEndPoint](../../../system.net/ipendpoint/)
* क्लास [UdpClient](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)