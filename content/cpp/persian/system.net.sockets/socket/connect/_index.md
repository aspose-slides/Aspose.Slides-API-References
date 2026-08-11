---
title: Connect()
second_title: Aspose.Slides برای C++ API Reference
description: اتصال به نقطهٔ انتهای از راه دور مشخص شده را برقرار می‌کند.
type: docs
weight: 560
url: /fa/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) متد

اتصال به نقطهٔ انتهای از راه دور مشخص شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطهٔ انتهای از راه دور. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) متد

اتصال به نقطهٔ انتهای از راه دور مشخص شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | آدرس IP میزبان از راه دور. |
| port | **int32_t** | شمارهٔ پورت میزبان از راه دور. |

## Socket::Connect(String, int32_t) متد

اتصال به نقطهٔ انتهای از راه دور مشخص شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | [String](../../../system/string/) | نام میزبان از راه دور. |
| port | **int32_t** | شمارهٔ پورت میزبان از راه دور. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) متد

اتصال به نقطهٔ انتهای از راه دور مشخص شده را برقرار می‌کند.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | آدرس‌های IP میزبان از راه دور. |
| port | **int32_t** | شمارهٔ پورت میزبان از راه دور. |

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [EndPoint](../../../system.net/endpoint/)
* کلاس [Socket](../)
* کلاس [IPAddress](../../../system.net/ipaddress/)
* کلاس [String](../../../system/string/)
* فضای نام [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)