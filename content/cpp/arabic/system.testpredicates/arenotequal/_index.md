---
title: AreNotEqual()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: المقارنة بعدم المساواة للوسائط لتأكيد AreEqual.
type: docs
weight: 40
url: /ar/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) دالة

الـ Not-equal تقارن الوسائط لتأكيد AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1\&& | قيمة LHS. |
| rhs | T2\&& | قيمة RHS. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضًا

* النطاق [System::TestPredicates](../)
* المكتبة [Aspose.Slides](../../)