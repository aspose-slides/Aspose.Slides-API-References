---
title: TryGetLast()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحاول الحصول على العنصر الأخير في المجموعة.
type: docs
weight: 261
url: /ar/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) دالة


تحاول الحصول على العنصر الأخير في المجموعة.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المجموعة. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | المجموعة التي يُراد الحصول منها على عنصر. |
| found | **bool**\& | المعامل الناتج. يُعيد true عندما تحتوي المجموعة على أي عنصر. وإلا يُعاد false. |

### قيمة الإرجاع

يُعيد العنصر الأخير في المجموعة. سيتم إرجاع القيمة الافتراضية للنوع عندما تكون المجموعة فارغة.

## انظر أيضًا

* الفئة [IEnumerable](../../system.collections.generic/ienumerable/)
* النطاق [System::Collections::Generic::Details](../)
* المكتبة [Aspose.Slides](../../)