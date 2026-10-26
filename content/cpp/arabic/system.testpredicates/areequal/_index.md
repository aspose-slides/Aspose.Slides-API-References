---
title: AreEqual()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن المتساوي الوسائط لتصريح AreEqual.
type: docs
weight: 14
url: /ar/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) دالة

يقارن المتساوي الوسائط لتصريح AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| T1 | نوع الكائن LHS. |
| T2 | نوع الكائن RHS. |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1\&& | قيمة LHS. |
| rhs | T2\&& | قيمة RHS. |

### قيمة الإرجاع

نتيجة التأكيد بنمط gtest.

## انظر أيضًا

* مساحة الاسم [System::TestPredicates](../)
* المكتبة [Aspose.Slides](../../)