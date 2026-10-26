---
title: TryGetFirst()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحاول الحصول على العنصر الأول من المجموعة.
type: docs
weight: 248
url: /ar/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) دالة


يحاول الحصول على العنصر الأول من المجموعة.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المجموعة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | المجموعة التي يُستخرج منها العنصر. |
| found | **bool**\& | معامل الإخراج. يُعيد true عندما تحتوي المجموعة على أي عنصر. وإلا يتم إرجاع false. |

### قيمة الإرجاع

يرجع العنصر الأول من المجموعة. سيتم إرجاع القيمة الافتراضية للنوع عندما تكون المجموعة فارغة.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) دالة


يحاول الحصول على العنصر الأول من المجموعة الذي يطابق دالة التحقق.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المجموعة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | المجموعة التي يُستخرج منها العنصر. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | دالة التحقق. |
| found | **bool**\& | معامل الإخراج. يُعيد true عندما تحتوي المجموعة على أي عنصر. وإلا يتم إرجاع false. |

### قيمة الإرجاع

يرجع العنصر الأول من المجموعة. سيتم إرجاع القيمة الافتراضية للنوع عندما لا يُعثر على عنصر يطابق دالة التحقق المحددة.

## انظر أيضًا

* الفئة [IEnumerable](../../system.collections.generic/ienumerable/)
* الفئة [Func](../../system/func/)
* النطاق [System::Collections::Generic::Details](../)
* المكتبة [Aspose.Slides](../../)