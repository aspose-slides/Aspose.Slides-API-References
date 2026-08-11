---
title: Compare()
second_title: Aspose.Slides للـ C++ مرجع API
description: يقارن قيمتين.
type: docs
weight: 2731
url: /ar/system/compare/
---
## System::Compare(const TA\&, const TB\&) دالة

يقارن قيمتين.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TA | نوع العنصر المقارن الأول |
| TB | نوع العنصر المقارن الثاني |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const TA\& | العنصر المقارن الأول |
| b | const TB\& | العنصر المقارن الثاني |

### قيمة الإرجاع

- 1 إذا كان **a** أصغر من **b**؛ 0 إذا كانت القيم متساوية؛ 1 إذا كان **a** أكبر من **b**

## System::Compare(const TA\&, const TB\&) دالة

يقارن قيمتين عائمتين.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TA | نوع العنصر المقارن الأول |
| TB | نوع العنصر المقارن الثاني |

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | const TA\& | العنصر المقارن الأول |
| b | const TB\& | العنصر المقارن الثاني |

### قيمة الإرجاع

- 1 إذا كان **a** أصغر من **b**؛ 0 إذا كانت القيم متساوية؛ 1 إذا كان **a** أكبر من **b**

## انظر أيضًا

* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)