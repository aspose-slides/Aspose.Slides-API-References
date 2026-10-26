---
title: Connect()
second_title: مرجع API Aspose.Slides برای C++
description: اتصال به پورت مشخص شده روی میزبان مشخص شده را برقرار می‌کند.
type: docs
weight: 66
url: /fa/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) متد

یک اتصال به پورت مشخص روی میزبان مشخص شده برقرار می‌کند.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | نام میزبان DNS راه دوری که می‌خواهید به آن متصل شوید. |
| port | **int32_t** | شماره پورت محلی که قصد برقراری ارتباط از طریق آن را دارید. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) متد

یک اتصال با میزبان در آدرس مشخص شده روی پورت مشخص شده برقرار می‌کند.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) میزبان راه دور که داده‌ها به آن ارسال می‌شود. |
| port | **int32_t** | شماره پورت محلی که قصد برقراری ارتباط از طریق آن را دارید. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) متد

یک اتصال به نقطه انتهایی از راه دور برقرار می‌کند.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | نقطه انتهایی که اتصال UDP به آن متصل می‌شود. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [UdpClient](../)
* کلاس [IPAddress](../../../system.net/ipaddress/)
* کلاس [IPEndPoint](../../../system.net/ipendpoint/)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)