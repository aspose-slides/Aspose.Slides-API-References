---
title: Connect()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بإنشاء اتصال بالنقطة النهائية البعيدة المحددة.
type: docs
weight: 560
url: /ar/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) طريقة

يقوم بإنشاء اتصال بالنقطة النهائية البعيدة المحددة.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | النقطة النهائية البعيدة. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) طريقة

يقوم بإنشاء اتصال بالنقطة النهائية البعيدة المحددة.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | عنوان IP للمضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |

## Socket::Connect(String, int32_t) طريقة

يقوم بإنشاء اتصال بالنقطة النهائية البعيدة المحددة.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) طريقة

يقوم بإنشاء اتصال بالنقطة النهائية البعيدة المحددة.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | عناوين IP للمضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [EndPoint](../../../system.net/endpoint/)
* فئة [Socket](../)
* فئة [IPAddress](../../../system.net/ipaddress/)
* فئة [String](../../../system/string/)
* مساحة اسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)