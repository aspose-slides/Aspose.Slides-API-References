---
title: SocketFlags
second_title: مرجع API Aspose.Slides برای C++
description: مقادیر ثابت برای پیام‌های سوکت را فراهم می‌کند.
type: docs
weight: 222
url: /fa/system.net.sockets/socketflags/
---
## SocketFlags enum

Provides constant values for the socket messages.

```cpp
enum class SocketFlags
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | برای این فراخوانی هیچ پرچمی استفاده نمی‌شود. |
| OutOfBand | 1 | داده‌های out-of-band در حال پردازش هستند. |
| Peek | 2 | نگاه کردن به یک پیام ورودی. |
| DontRoute | 4 | ارسال پیام بدون استفاده از جداول مسیریابی. |
| Truncated | 256 | پیام بیش از حد بزرگ است تا در بافر مشخص شده جای بگیرد. پیام کوتاه شده است. |
| ControlDataTruncated | 512 | داده‌های کنترل بیشتر از 64 کیلوبایت است و در بافر داخلی جا نمی‌شود. داده‌ها کوتاه شده‌اند. |
| Broadcast | 1024 | بسته پخش (broadcast). |
| Multicast | 2048 | بسته چندپخشی (multicast). |
| Partial | 32768 | پیام به صورت جزئی ارسال یا دریافت شده است. |

## موارد مرتبط

* فضای نام [System::Net::Sockets](../)
* کتابخانه [Aspose.Slides](../../)