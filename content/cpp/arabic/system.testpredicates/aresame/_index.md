---
title: AreSame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن Are-same المعلمات لتأكيد AreSame.
type: docs
weight: 66
url: /ar/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) دالة


Are-same-compares arguments for AreSame assertion translation.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن LHS. |
| T2 | نوع الكائن RHS. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |

### قيمة الإرجاع

نتيجة التأكيد بنمط gtest.

## انظر أيضًا

* النطاق [System::TestPredicates](../)
* المكتبة [Aspose.Slides](../../)