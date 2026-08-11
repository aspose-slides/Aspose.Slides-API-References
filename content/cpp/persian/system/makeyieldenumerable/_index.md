---
title: MakeYieldEnumerable()
second_title: مرجع API Aspose.Slides برای C++
description: یک IEnumerable را از یک تابع yield ایجاد می‌کند.
type: docs
weight: 2419
url: /fa/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

یک IEnumerable را از یک تابع yield ایجاد می‌کند.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در دنباله |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | تابع yield برای اجرا |

### مقدار بازگشت

اشاره‌گر مشترک به IEnumerable

## موارد مرتبط

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)