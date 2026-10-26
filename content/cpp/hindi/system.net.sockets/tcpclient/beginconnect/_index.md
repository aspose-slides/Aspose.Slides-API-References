---
title: BeginConnect()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।
type: docs
weight: 261
url: /hi/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि


एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | एक रिमोट होस्ट नाम। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन पूर्ण होने पर कॉल होगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता-द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को अद्वितीय रूप से पहचानता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि


एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | रिमोट होस्ट का IP पता। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन पूर्ण होने पर कॉल होगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता-द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को अद्वितीय रूप से पहचानता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) विधि


एक असिंक्रोनस कनेक्ट ऑपरेशन शुरू करता है।

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | रिमोट होस्ट के IP पते। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट। |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | एक कॉलबैक जो ऑपरेशन पूर्ण होने पर कॉल होगा। |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | उपयोगकर्ता-द्वारा प्रदान किया गया डेटा जो प्रत्येक असिंक्रोनस कनेक्ट ऑपरेशन को अद्वितीय रूप से पहचानता है। |

### रिटर्न मान

एक [IAsyncResult](../../../system/iasyncresult/) ऑब्जेक्ट जो प्रारंभ किए गए असिंक्रोनस कनेक्ट ऑपरेशन का प्रतिनिधित्व करता है।

## और देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [AsyncCallback](../../../system/asynccallback/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [IAsyncResult](../../../system/iasyncresult/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [TcpClient](../)
* क्लास [IPAddress](../../../system.net/ipaddress/)
* नेमस्पेस [System::Net::Sockets](../../)
* लाइब्रेरी [Aspose.Slides](../../../)