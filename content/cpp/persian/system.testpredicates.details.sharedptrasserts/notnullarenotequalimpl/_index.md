---
title: NotNullAreNotEqualImpl()
second_title: مرجع API Aspose.Slides برای C++
description: مقایسه نا برابر آرایه‌ها یا لیست‌ها.
type: docs
weight: 105
url: /fa/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


مقایسه نا برابر آرایه‌ها یا لیست‌ها.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | نوع کانتینر LHS. |
| T2 | نوع کانتینر RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | پارامتر سرویس که به‌عنوان انتخاب‌کننده پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### Return Value

نتیجهٔ ادعایی به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


مقایسه نا برابر نمونه‌های IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | نوع عنصر LHS. |
| T2 | نوع عنصر RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | پارامتر سرویس که به‌عنوان انتخاب‌کننده پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### Return Value

نتیجهٔ ادعایی به سبک gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function


مقایسه نا برابر انواع ناشناخته با استفاده از متد Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |

### Return Value

نتیجهٔ ادعایی به سبک gtest.

## See Also

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)