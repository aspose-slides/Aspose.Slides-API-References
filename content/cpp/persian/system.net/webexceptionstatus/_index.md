---
title: WebExceptionStatus
second_title: Aspose.Slides برای مرجع API C++
description: کدهای وضعیت کلاس WebException را فهرست می‌کند.
type: docs
weight: 651
url: /fa/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

کدهای وضعیت کلاس WebException را فهرست می‌کند.

```cpp
enum class WebExceptionStatus
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Success | 0 | خطایی رخ نداد. |
| NameResolutionFailure | 1 | سرویس حل‌گر نام نتوانست نام میزبان را حل کند. |
| ConnectFailure | 2 | نقطه سرویس ریموت نتوانست در سطح حمل‌ونقل تماس بگیرد. |
| ReceiveFailure | 3 | پاسخ کامل از سرور ریموت دریافت نشد. |
| SendFailure | 4 | درخواست کامل نتوانست به سرور ریموت ارسال شود. |
| PipelineFailure | 5 | درخواست یک درخواست خط لوله‌ای بود و قبل از دریافت پاسخ، اتصال بسته شد. |
| RequestCanceled | 6 | درخواست لغو شد یا خطایی غیرقابل طبقه‌بندی رخ داد. |
| ProtocolError | 7 | پاسخی که از سرور دریافت شد کامل بود اما خطای سطح پروتکل را نشان داد. |
| ConnectionClosed | 8 | اتصال پیش از موعد بسته شد. |
| TrustFailure | 9 | گواهی سرور نتوانست اعتبارسنجی شود. |
| SecureChannelFailure | 10 | خطایی هنگام برقراری اتصال با استفاده از SSL رخ داد. |
| ServerProtocolViolation | 11 | پاسخ سرور یک پاسخ HTTP معتبر نبود. |
| KeepAliveFailure | 12 | اتصال برای درخواست‌ایی که هدر 'Keep-Alive' را مشخص کرده بود به‌طور غیرمنتظره بسته شد. |
| Pending | 13 | درخواستی داخلی ناهمزمان در حالت انتظار است. |
| Timeout | 14 | در طول زمان‌سنجی برای یک درخواست، پاسخی دریافت نشد. |
| ProxyNameResolutionFailure | 15 | سرویس حل‌گر نام نتوانست نام میزبان پراکسی را حل کند. |
| UnknownError | 16 | یک استثنا از نوع ناشناخته رخ داده است. |
| MessageLengthLimitExceeded | 17 | پیغامی که از حد مشخص‌شده فراتر رفت دریافت شد. |
| CacheEntryNotFound | 18 | ورودی کش مشخص‌شده پیدا نشد. |
| RequestProhibitedByCachePolicy | 19 | درخواست توسط سیاست کش اجازه داده نشد. |
| RequestProhibitedByProxy | 20 | این درخواست توسط پراکسی اجازه داده نشد. |

## مراجعه

* فضای‌نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)