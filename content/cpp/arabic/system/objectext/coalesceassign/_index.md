---
title: CoalesceAssign()
second_title: مرجع API Aspose.Slides للغة C++
description: تنفيذ ترجمة عامل '??='.
type: docs
weight: 183
url: /ar/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) طريقة

تنفيذ ترجمة عامل '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T0 | نوع قيمة LHS. |
| T1 | نوع lambda الذي يضمن تعبير RHS. |

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | T0\& | قيمة LHS. |
| func | T1 | تعبير RHS. |

### قيمة الإرجاع

إذا كانت قيمة LHS ليست فارغة، تُرجِع LHS، وإلا يتم حساب تعبير RHS وتُرجِع النتيجة.

## انظر أيضًا

* الفئة [ObjectExt](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)