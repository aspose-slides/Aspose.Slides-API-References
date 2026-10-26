---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस स्वीकृति ऑपरेशन शुरू करता है।
type: docs
weight: 170
url: /hi/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस स्वीकृति ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन के पूरा होने पर कॉल किया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया जाता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस स्वीकृति ऑपरेशन का प्रतिनिधित्व करता है।

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [TcpListener](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)