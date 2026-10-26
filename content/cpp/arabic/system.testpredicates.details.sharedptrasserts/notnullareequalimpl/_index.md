---
title: NotNullAreEqualImpl()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن بالتساوي بين المصفوفات أو القوائم.
type: docs
weight: 40
url: /ar/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) دالة

يقارن بالتساوي بين المصفوفات أو القوائم.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | نوع الحاوية على الجانب الأيسر. |
| T2 | نوع الحاوية على الجانب الأيمن. |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) دالة

يقارن بالتساوي بين مثيلات IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | نوع العنصر في الجانب الأيسر. |
| T2 | نوع العنصر في الجانب الأيمن. |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, int32_t) دالة

يقارن بالتساوي الأنواع غير المعروفة باستخدام طريقة Equals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | نوع الكائن في الجانب الأيسر. |
| T2 | نوع الكائن في الجانب الأيمن. |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضًا

* تعريف نوع [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* تعريف نوع [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* هيكل [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* مساحة أسماء [System::TestPredicates::Details::SharedPtrAsserts](../)
* مكتبة [Aspose.Slides](../../)