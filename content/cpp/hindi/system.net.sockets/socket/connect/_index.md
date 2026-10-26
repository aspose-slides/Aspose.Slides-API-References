---
title: Connect()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट रिमोट एंडपॉइंट के साथ एक कनेक्शन स्थापित करता है।
type: docs
weight: 560
url: /hi/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) विधि


रिमोट एंडपॉइंट से कनेक्शन स्थापित करता है.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | रिमोट एंडपॉइंट। |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) विधि


रिमोट एंडपॉइंट से कनेक्शन स्थापित करता है.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | रिमोट होस्ट का IP पता। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |

## Socket::Connect(String, int32_t) विधि


रिमोट एंडपॉइंट से कनेक्शन स्थापित करता है.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | रिमोट होस्ट का नाम। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) विधि


रिमोट एंडपॉइंट से कनेक्शन स्थापित करता है.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | रिमोट होस्ट के IP पते। |
| port | **int32_t** | रिमोट होस्ट का पोर्ट नंबर। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)