---
title: UdpClient()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس UdpClient را ایجاد می‌کند.
type: docs
weight: 27
url: /fa/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() سازنده

یک نمونه جدید از کلاس [UdpClient](../) را ایجاد می‌کند.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) سازنده

یک نمونه جدید از کلاس [UdpClient](../) را ایجاد می‌کند.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | مقداری که طرح نشانی‌گذاری سوکت را مشخص می‌کند. |

## UdpClient::UdpClient(int32_t) سازنده

یک نمونه جدید از کلاس [UdpClient](../) را ایجاد می‌کند.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| port | **int32_t** | شماره پورت محلی که قصد دارید از آن ارتباط برقرار کنید. |

## UdpClient::UdpClient(int32_t, AddressFamily) سازنده

یک نمونه جدید از کلاس [UdpClient](../) را ایجاد می‌کند.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| port | **int32_t** | شماره پورت محلی که قصد دارید از آن ارتباط برقرار کنید. |
| family | [AddressFamily](../../addressfamily/) | مقداری که طرح نشانی‌گذاری سوکت را مشخص می‌کند. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) سازنده

یک نمونه جدید از کلاس [UdpClient](../) را ایجاد می‌کند. param local EP نقطه انتهایی محلی که اتصال UDP به آن متصل می‌شود.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) سازنده

یک نمونه جدید از کلاس [UdpClient](../) ایجاد می‌کند و به میزبان از راه دور مشخص شده در پورت تعیین‌شده متصل می‌شود.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | نام میزبان DNS از راه دور که قصد دارید به آن متصل شوید. |
| port | **int32_t** | شماره پورت محلی که قصد دارید از آن ارتباط برقرار کنید. |

## موارد مرتبط

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)