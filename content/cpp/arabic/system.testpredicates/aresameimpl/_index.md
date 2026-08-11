---
title: AreSameImpl()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: Are-same تقارن المؤشرات الذكية.
type: docs
weight: 79
url: /ar/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة

Are-same تقارن المؤشرات الذكية.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمنقِّط لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة

Are-same تقارن الاستثناءات.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمنقِّط لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) دالة

Are-same تقارن القيم غير المؤشرية.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضاً

* هيكل [IsSmartPtr](../../system/issmartptr/)
* هيكل [IsExceptionWrapper](../../system/isexceptionwrapper/)
* نطاق [System::TestPredicates](../)
* مكتبة [Aspose.Slides](../../)