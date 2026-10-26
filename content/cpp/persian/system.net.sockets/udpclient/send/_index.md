---
title: Send()
second_title: مرجع API Aspose.Slides برای C++
description: یک دیتاگرام UDP را به میزبان در نقطه انتهایی دور ارسال می‌کند.
type: docs
weight: 79
url: /fa/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) متد

یک دیتاگرام UDP را به میزبان در نقطه انتهایی دور ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک آرایه از نوع [Byte](../../../system/byte/) برای ارسال |
| bytes | **int32_t** | تعداد بایت‌ها در دیتاگرام. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | یک [IPEndPoint](../../../system.net/ipendpoint/) که میزبان و پورت مقصد ارسال دیتاگرام را نشان می‌دهد. |

### مقدار بازگشتی

تعداد بایت‌هایی که ارسال می‌شوند.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) متد

یک دیتاگرام UDP را به پورت مشخص روی میزبان دوردست مشخص ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک آرایه از نوع [Byte](../../../system/byte/) برای ارسال |
| bytes | **int32_t** | تعداد بایت‌ها در دیتاگرام. |
| hostname | [String](../../../system/string/) | یک نام برای میزبان دوردست. |
| port | **int32_t** | یک شماره پورت دوردست. |

### مقدار بازگشتی

تعداد بایت‌هایی که ارسال می‌شوند.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) متد

یک دیتاگرام UDP را به یک میزبان دوردست ارسال می‌کند.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک آرایه از نوع [Byte](../../../system/byte/) برای ارسال. |
| bytes | **int32_t** | تعداد بایت‌ها در دیتاگرام. |

### مقدار بازگشتی

تعداد بایت‌هایی که ارسال می‌شوند.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)