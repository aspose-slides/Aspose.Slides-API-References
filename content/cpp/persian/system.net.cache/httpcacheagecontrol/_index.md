---
title: HttpCacheAgeControl
second_title: Aspose.Slides برای مرجع API C++
description: CacheAgeControl برای تعیین ترجیحات مرتبط با سن و تازگی موارد کش شده استفاده می‌شود.
type: docs
weight: 53
url: /fa/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl برای تعیین ترجیحات مرتبط با سن و تازگی موارد کش شده استفاده می‌شود.

```cpp
enum class HttpCacheAgeControl
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | فقط برای استفاده داخلی. |
| MinFresh | 1 | در صورتیکه زمان باقی‌مانده تا انقضا برابر یا بیشتر از زمان مشخص‌شده با این مقدار باشد، محتوا می‌تواند از کش گرفته شود. |
| MaxAge | 2 | محتوا می‌تواند تا زمانی که از سنی که با این مقدار تعیین شده قدیمی‌تر شود، از کش گرفته شود. |
| MaxStale | 4 | پس از انقضای محتوا، می‌توان تا پایان زمان مشخص‌شده با این مقدار، از کش دریافت کرد. |
| MaxAgeAndMinFresh | 3 | MaxAge و MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge و MaxStale. |

## See Also

* فضای نام [System::Net::Cache](../)
* کتابخانه [Aspose.Slides](../../)