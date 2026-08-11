---
title: MakeYieldEnumerable()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينشئ IEnumerable من دالة yield.
type: docs
weight: 2419
url: /ar/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) دالة

إنشاء IEnumerable من دالة yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في التسلسل |

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | دالة yield للتنفيذ |

### قيمة الإرجاع

مؤشر مشترك إلى IEnumerable

## انظر أيضًا

* تعريف نوع [SharedPtr](../sharedptr/)
* فئة [IEnumerable](../../system.collections.generic/ienumerable/)
* نطاق الاسم [System](../)
* مكتبة [Aspose.Slides](../../)