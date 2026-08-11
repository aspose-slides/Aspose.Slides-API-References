---
title: DateTimeStyles
second_title: Aspose.Slides برای مرجع API C++
description: گزینه‌های قالب‌بندی تاریخ و زمان را تعریف می‌کند. پرچم‌های بیتی.
type: docs
weight: 456
url: /fa/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Defines date and time formatting options. Bit flags.

```cpp
enum class DateTimeStyles : int32_t
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | پیش‌فرض. |
| AllowLeadingWhite | 1 | نادیده گرفتن فضاهای سفید پیشرو. |
| AllowTrailingWhite | 2 | نادیده گرفتن فضاهای سفید انتهایی. |
| AllowInnerWhite | 4 | نادیده گرفتن فضاهای سفید داخلی. |
| AllowWhiteSpaces | n/a | نادیده گرفتن تمام فضاهای سفید. |
| NoCurrentDateDefault | 8 | در زمان تجزیهٔ رشتهٔ تاریخ/زمان، اگر تمام سال/ماه/روز موجود نباشد، تاریخ پیش‌فرض را به 0001/1/1 تنظیم می‌کند، نه به سال/ماه/روز جاری. |
| AdjustToUniversal | 16 | در زمان تجزیهٔ رشتهٔ تاریخ/زمان، اگر مشخص‌گر منطقهٔ زمانی ("GMT","Z","+xxxx", "-xxxx" وجود داشته باشد)، زمان تجزیه‌شده را بر اساس GMT تنظیم می‌کنیم. |
| AssumeLocal | 32 | اگر منطقهٔ زمانی ارائه نشده باشد، از منطقهٔ زمانی محلی استفاده می‌کند. |
| AssumeUniversal | 64 | اگر منطقهٔ زمانی ارائه نشده باشد، از UTC استفاده می‌کند. |
| RoundtripKind | 128 | تلاش برای حفظ اینکه ورودی نامشخص، محلی یا UTC است. |

## موارد مرتبط

* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)