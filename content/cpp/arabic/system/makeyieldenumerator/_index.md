---
title: MakeYieldEnumerator()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ IEnumerator من دالة عائد.
type: docs
weight: 2432
url: /ar/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) دالة

ينشئ IEnumerator من دالة العائد.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع العناصر في التسلسل |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | دالة العائد للتنفيذ |

### قيمة الإرجاع

مؤشر مشترك إلى IEnumerator

## انظر أيضاً

* تعريف نوع [SharedPtr](../sharedptr/)
* فئة [IEnumerator](../../system.collections.generic/ienumerator/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)