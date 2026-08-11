---
title: AreFPNaN()
second_title: Aspose.Slides برای C++ مرجع API
description: فضای نام Details
type: docs
weight: 1
url: /fa/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) تابع

namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | اولین نوع عدد اعشاری. |
| T2 | دومین نوع عدد اعشاری. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | T1 | اولین مقدار عدد اعشاری. |
| rhs | T2 | دومین مقدار عدد اعشاری. |

### مقدار بازگشت

True اگر هر دو **lhs** و **rhs** مقدار عدد اعشاری باشند، false در غیر این صورت.

## ملاحظات

بررسی می‌کند که دو مقدار عدد اعشاری هر دو NaN باشند. وضعیت NaN بدون سیگنال که پشتیبانی می‌شود را مدیریت می‌کند.

## System::TestPredicates::AreFPNaN(T1, T2) تابع

بررسی می‌کند که دو مقدار عدد اعشاری هر دو NaN باشند. وضعیت NaN بدون سیگنال که پشتیبانی نمی‌شود را مدیریت می‌کند.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | اولین نوع عدد اعشاری. |
| T2 | دومین نوع عدد اعشاری. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs | T1 | اولین مقدار عدد اعشاری. |
| rhs | T2 | دومین مقدار عدد اعشاری. |

### مقدار بازگشت

همیشه false را برمی‌گرداند زیرا مقدار NaN پشتیبانی نمی‌شود.

## مراجع

* فضای نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)