---
title: AreSameImpl()
second_title: مرجع API Aspose.Slides برای C++
description: Are-same مقایسهٔ اشاره‌گرهای هوشمند را انجام می‌دهد.
type: docs
weight: 79
url: /fa/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same مقایسهٔ اشاره‌گرهای هوشمند را انجام می‌دهد.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | پارامتر سرویسی که به‌عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same مقایسهٔ استثناها را انجام می‌دهد.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | پارامتر سرویسی که به‌عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعا به سبک gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

Are-same مقایسهٔ مقادیر غیر اشاره‌گر را انجام می‌دهد.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |

### مقدار بازگشت

نتیجهٔ ادعا به سبک gtest.

## نگاه کنید به

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)