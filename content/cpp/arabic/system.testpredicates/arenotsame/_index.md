---
title: AreNotSame()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: Are-not-same-compares تُقارن المعاملات لتصريح AreSame.
type: docs
weight: 92
url: /ar/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) دالة


Are-not-same-compares يَقارِن المعاملات لتصريح AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الكائن LHS. |
| T2 | نوع الكائن RHS. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |

### قيمة الإرجاع

gtest-styled نتيجة التأكيد.

## انظر أيضًا

* نطاق [System::TestPredicates](../)
* مكتبة [Aspose.Slides](../../)