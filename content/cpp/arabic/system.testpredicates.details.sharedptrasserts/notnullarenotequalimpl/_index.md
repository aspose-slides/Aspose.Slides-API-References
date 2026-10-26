---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides لمرجع API C++
description: مقارنة عدم التساوي للمصفوفات أو القوائم.
type: docs
weight: 105
url: /ar/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


يقارن عدم التساوي بين المصفوفات أو القوائم.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع حاوية LHS. |
| T2 | نوع حاوية RHS. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يعمل كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


يقارن عدم التساوي بين كائنات IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع عنصر LHS. |
| T2 | نوع عنصر RHS. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يعمل كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) دالة


يقارن عدم التساوي بين الأنواع غير المعروفة باستخدام طريقة Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع كائن LHS. |
| T2 | نوع كائن RHS. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضاً

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)