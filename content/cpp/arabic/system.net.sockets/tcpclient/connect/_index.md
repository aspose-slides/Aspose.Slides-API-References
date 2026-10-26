---
title: Connect()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يقوم بإنشاء اتصال بالمضيف البعيد المحدد.
type: docs
weight: 248
url: /ar/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) طريقة

يقوم بإنشاء اتصال بالمضيف البعيد المحدد.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | اسم مضيف بعيد للاتصال به. |
| port | **int32_t** | منفذ المضيف البعيد للاتصال به. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) طريقة

يقوم بإنشاء اتصال بالمضيف البعيد المحدد.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | عنوان IP لمضيف بعيد. |
| port | **int32_t** | منفذ المضيف البعيد للاتصال به. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) طريقة

يقوم بإنشاء اتصال بالمضيف البعيد المحدد.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | مضيف بعيد للاتصال به. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) طريقة

يقوم بإنشاء اتصال بالمضيف البعيد المحدد.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | عناوين IP لمضيف بعيد. |
| port | **int32_t** | منفذ المضيف البعيد للاتصال به. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [TcpClient](../)
* فئة [IPAddress](../../../system.net/ipaddress/)
* فئة [IPEndPoint](../../../system.net/ipendpoint/)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)