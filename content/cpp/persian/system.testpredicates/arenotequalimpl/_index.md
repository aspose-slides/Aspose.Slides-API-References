---
title: AreNotEqualImpl()
second_title: Aspose.Slides برای C++ مرجع API
description: مقایسه‌نامساوی مقادیر که یکی یا هر دو آن‌ها Decimal هستند.
type: docs
weight: 53
url: /fa/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع

مقایسه‌نامساوی مقادیر، یکی یا هر دو آنها [Decimal](../../system/decimal/) هستند.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء سمت چپ. |
| T2 | نوع شیء سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1\& | مقدار سمت چپ. |
| rhs | const T2\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع

مقایسه‌نامساوی انواع غیر اشاره‌گر با استفاده از متد Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) تابع

مقایسه‌نامساوی انواع غیر اشاره‌گر با استفاده از متد Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع

مقایسه‌نامساوی انواع غیر اشاره‌گر با استفاده از عملگر != ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) تابع

مقایسه‌نامساوی مقادیر قابل جعبه‌گذاری با [SmartPtr](../../system/smartptr/) با استفاده از حذف جعبه‌گذاری.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T | مقدار سمت چپ. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) تابع

مقایسه‌نامساوی مقادیر قابل جعبه‌گذاری با [SmartPtr](../../system/smartptr/) با استفاده از حذف جعبه‌گذاری.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت چپ. |
| rhs | T | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) تابع

مقایسه‌نامساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T | مقدار سمت چپ. |
| s | std::nullptr_t | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) تابع

مقایسه‌نامساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| rhs | std::nullptr_t | مقدار سمت راست. |
| s | T | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع

مقایسه‌برابر انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1\& | مقدار سمت چپ. |
| rhs | const T2\& | مقدار سمت راست. |
| s | long long | پارامتر سرویس که به عنوان انتخاب‌گر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) تابع

مقایسه‌برابر انواع تصادفی با استفاده از الگوریتم‌های gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T1 | مقدار سمت چپ. |
| rhs | T2 | مقدار سمت راست. |

### مقدار بازگشتی

نتیجه‌ی اطمینان‌ساز به سبک gtest.

## موارد مرتبط

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)