---
title: SameFailure()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتنسيق فشل التأكيد 'same' للإخراج.
type: docs
weight: 53
url: /ar/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) دالة

يقوم بتنسيق فشل التأكيد 'same' للإخراج.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع قيمة LHS. |
| T2 | نوع قيمة RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1\& | قيمة LHS. |
| rhs | T2\& | قيمة RHS. |

### قيمة الإرجاع

[Object](../../system/object/) نص الفشل المغلف.

## انظر أيضًا

* نطاق [System::TestPredicates::Details](../)
* مكتبة [Aspose.Slides](../../)