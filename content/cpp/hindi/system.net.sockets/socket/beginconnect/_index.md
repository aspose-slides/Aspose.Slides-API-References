---
title: BeginConnect()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।
type: docs
weight: 573
url: /hi/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामिटर | टाइप | विवरण |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |
| callback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन के पूरा होने पर बुलाया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामिटर | टाइप | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | रिमोट होस्ट का नाम। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन के पूरा होने पर बुलाया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामिटर | टाइप | विवरण |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | रिमोट होस्ट का IP पता। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन के पूरा होने पर बुलाया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि

एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### आर्ग्युमेंट्स

| पैरामिटर | टाइप | विवरण |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | रिमोट होस्ट के IP पते। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन के पूरा होने पर बुलाया जाएगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता द्वारा प्रदान किया गया डेटा, जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को विशिष्ट रूप से पहचानने के लिए उपयोग होता है। |

### रिटर्न वैल्यू

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो शुरू किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [EndPoint](../../../system.net/endpoint/)
* क्लास [Object](../../../system/object/)
* क्लास [Socket](../)
* क्लास [String](../../../system/string/)
* क्लास [IPAddress](../../../system.net/ipaddress/)
* नेमस्पेस [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)