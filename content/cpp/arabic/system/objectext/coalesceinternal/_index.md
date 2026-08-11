---
title: CoalesceInternal()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تنفيذ ترجمة عامل '??' للأنواع غير القابلة للإلغاء. إصدار بديل للحالة إذا كان RT2 قابلًا للتحويل إلى RT1.
type: docs
weight: 157
url: /ar/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) طريقة

Implementation of '??' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T0 | نوع قيمة LHS. |
| T1 | نوع lambda التي تغلف تعبير RHS. |

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | RT1 | قيمة LHS. |
| func | F | تعبير RHS. |

### قيمة الإرجاع

إذا كانت قيمة LHS ليست null، تُرجع LHS، وإلا تحسب تعبير RHS وتُعيد النتيجة.

## انظر أيضاً

* الفئة [ObjectExt](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)