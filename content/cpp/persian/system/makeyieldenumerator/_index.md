---
title: MakeYieldEnumerator()
second_title: Aspose.Slides برای C++ مرجع API
description: یک IEnumerator از یک تابع yield ایجاد می‌کند.
type: docs
weight: 2432
url: /fa/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) تابع

یک IEnumerator از یک تابع yield ایجاد می‌کند.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در توالی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | تابع yield برای اجرا |

### مقدار برگشتی

اشاره‌گر مشترک به IEnumerator

## موارد مرتبط

* تعریف نوع [SharedPtr](../sharedptr/)
* کلاس [IEnumerator](../../system.collections.generic/ienumerator/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)