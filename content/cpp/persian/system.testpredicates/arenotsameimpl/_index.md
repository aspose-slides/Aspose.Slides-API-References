---
title: AreNotSameImpl()
second_title: Aspose.Slides برای C++ مرجع API
description: Are-not-same مقایسه‌ی اشاره‌گرهای هوشمند.
type: docs
weight: 105
url: /fa/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع


Are-not-same مقایسه‌ی اشاره‌گرهای هوشمند.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شی LHS. |
| T2 | نوع شی RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) تابع


Are-not-same مقایسه‌ی مقادیر غیر اشاره‌گر.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شی LHS. |
| T2 | نوع شی RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## موارد مرتبط

* ساختار [IsSmartPtr](../../system/issmartptr/)
* فضای‌نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)