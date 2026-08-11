---
title: CoalesceInternal()
second_title: Aspose.Slides برای C++ مرجع API
description: پیاده‌سازی ترجمه‌ی عملگر '??' برای انواع غیرقابل تهی. بارگذاری مجدد برای حالت اگر RT2 قابل تبدیل به RT1 باشد.
type: docs
weight: 157
url: /fa/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) متد

پیاده‌سازی ترجمه‌ی عملگر '??' برای انواع غیرقابل تهی. بارگذاری مجدد برای حالت اگر RT2 قابل تبدیل به RT1 باشد.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T0 | نوع مقدار LHS. |
| T1 | نوع lambda که عبارت RHS را در بر می‌گیرد. |

### آرگومان‌ها

| پارامتر | Type | توضیح |
| --- | --- | --- |
| value | RT1 | مقدار LHS. |
| func | F | عبارت RHS. |

### مقدار برگشتی

اگر مقدار LHS غیر تهی باشد، LHS را برمی‌گرداند، در غیر این صورت عبارت RHS را محاسبه کرده و نتیجه را برمی‌گرداند.

## مراجعه

* کلاس [ObjectExt](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)