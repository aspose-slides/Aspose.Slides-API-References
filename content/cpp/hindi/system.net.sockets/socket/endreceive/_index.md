---
title: EndReceive()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित असिंक्रोनस रिसीव ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है।
type: docs
weight: 534
url: /hi/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) विधि

निर्दिष्ट असिंक्रोनस रिसीव ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है।

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस रिसीव ऑपरेशन का प्रतिनिधित्व करता है। |

### रिटर्न मान

प्राप्त बाइट्स की संख्या।

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) विधि

निर्दिष्ट असिंक्रोनस रिसीव ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है।

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस रिसीव ऑपरेशन का प्रतिनिधित्व करता है। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड को असाइन किया जाएगा जब रिसीव ऑपरेशन विफल हो जाता है। |

### रिटर्न मान

प्राप्त बाइट्स की संख्या।

## संबंधित देखें

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)