---
title: SpecifyKind()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء جدید DateTime می‌سازد که همان تعداد تیک‌ها را همانند شیء DateTime مشخص‌شده نشان می‌دهد و زمان محلی، زمان UTC یا هیچ‌کدام را بر حسب آرگومان kind مشخص می‌کند.
type: docs
weight: 833
url: /fa/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) متد

یک شیٔ جدید از نوع [DateTime](../) می‌سازد که تعداد همان تیک‌ها را همانند شیٔ [DateTime](../) مشخص‌شده نمایان می‌کند و زمان محلی، زمان UTC یا هیچ‌کدام را بر حسب آرگومان **kind** مشخص می‌کند.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | شیٔ [DateTime](../) برای کپی کردن تعداد تیک‌ها از آن |
| kind | [DateTimeKind](../../datetimekind/) | مشخص می‌کند که آیا شیٔ جدید باید زمان محلی، زمان UTC یا هیچ‌کدام را نمایان کند. |

### مقدار بازگشت

یک شیٔ جدید از نوع [DateTime](../) که همان تعداد تیک‌هایی که **value** دارد و مقدار DateTimeKind که توسط **kind** مشخص شده را نمایان می‌کند.

## موارد مرتبط

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)