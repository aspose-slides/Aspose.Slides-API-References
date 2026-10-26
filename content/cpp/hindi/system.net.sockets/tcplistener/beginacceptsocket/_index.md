---
title: BeginAcceptSocket()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: एक असिंक्रोनस स्वीकृति ऑपरेशन शुरू करता है।
type: docs
weight: 144
url: /hi/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस स्वीकृति ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | जब ऑपरेशन पूरा हो जाए तो कॉल किया जाने वाला कॉलबैक। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग किया जाता है। |

### वापसी मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस स्वीकृति ऑपरेशन को दर्शाता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [AsyncCallback](../../../system/asynccallback/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [Object](../../../system/object/)
* क्लास [TcpListener](../)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)