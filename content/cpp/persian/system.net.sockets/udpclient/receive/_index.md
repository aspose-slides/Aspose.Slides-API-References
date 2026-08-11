---
title: Receive()
second_title: Aspose.Slides برای C++ مرجع API
description: یک دیتاگرام که توسط سرور ارسال شده است را برمی‌گرداند.
type: docs
weight: 92
url: /fa/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) متد

یک دیتاگرام که توسط سرور ارسال شده است را برمی‌گرداند.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | [IPEndPoint](../../../system.net/ipendpoint/) که میزبان ریموتی را که داده‌ها از آن ارسال شده‌اند، نمایش می‌دهد. |

### مقدار بازگشتی

یک آرایه بایت که داده‌های دریافت‌شده در آن اختصاص می‌یابد.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPEndPoint](../../../system.net/ipendpoint/)
* کلاس [UdpClient](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)