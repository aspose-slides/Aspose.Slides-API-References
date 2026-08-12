---
title: EndSend()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट असिंक्रोनस भेजने वाले ऑपरेशन के पूरा होने तक प्रतीक्षा करता है।
type: docs
weight: 508
url: /hi/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) विधि

निर्दिष्ट असिंक्रोनस भेजने के ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है।

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस भेजने के ऑपरेशन का प्रतिनिधित्व करता है। |

### Return Value

भेजे गए बाइट्स की संख्या।

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) विधि

निर्दिष्ट असिंक्रोनस भेजने के ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है।

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो एक असिंक्रोनस भेजने के ऑपरेशन का प्रतिनिधित्व करता है। |
| errorCode | [SocketError](../../socketerror/)\& | आउटपुट पैरामीटर जहाँ त्रुटि कोड को असाइन किया जाएगा जब भेजने का ऑपरेशन विफल हो जाता है। |

### Return Value

भेजे गए बाइट्स की संख्या।

## देखें

* एनम [SocketError](../../socketerror/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Socket](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)