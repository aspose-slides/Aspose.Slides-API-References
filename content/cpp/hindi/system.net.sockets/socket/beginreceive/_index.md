---
title: BeginReceive()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस लिखने का संचालन आरंभ करता है।
type: docs
weight: 521
url: /hi/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस लिखने का संचालन आरंभ करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | प्राप्त डेटा को सौंपा जाने वाला बफ़र। |
| offset | **int32_t** | निर्दिष्ट एरे में बाइट्स में ऑफ़सेट। |
| size | **int32_t** | 'ऑफ़सेट' पैरामीटर से शुरू होकर निर्दिष्ट एरे में बाइट्स की संख्या। |
| socketFlags | [SocketFlags](../../socketflags/) | रिसीव व्यवहार। |
| callback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो संचालन पूरा होने पर कॉल किया जाता है। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता-द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस रिसीव संचालन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस रिसीव संचालन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)