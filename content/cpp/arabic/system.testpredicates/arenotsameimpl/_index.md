---
title: AreNotSameImpl()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: Are-not-same تقارن المؤشرات الذكية.
type: docs
weight: 105
url: /ar/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


Are-not-same تقارن المؤشرات الذكية.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يعمل كمنتقٍ لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) دالة


Are-not-same تقارن القيم غير المؤشرية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |

### قيمة الإرجاع

gtest-styled assertion result.

## انظر أيضًا

* بنية [IsSmartPtr](../../system/issmartptr/)
* نطاق [System::TestPredicates](../)
* مكتبة [Aspose.Slides](../../)