---
title: NotSameFailure()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتنسيق فشل تأكيد 'ليس نفسه' للإخراج.
type: docs
weight: 66
url: /ar/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) دالة

يُنسّق فشل تأكيد 'ليس نفسه' للإخراج.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### معلمات القالب

| معاملة | الوصف |
| --- | --- |
| T1 | نوع قيمة LHS. |
| T2 | نوع قيمة RHS. |

### وسائط

| معاملة | نوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1\& | قيمة LHS. |
| rhs | T2\& | قيمة RHS. |

### قيمة الإرجاع

[Object](../../system/object/) التي تغلف نص الفشل.

## انظر أيضاً

* النطاق [System::TestPredicates::Details](../)
* المكتبة [Aspose.Slides](../../)