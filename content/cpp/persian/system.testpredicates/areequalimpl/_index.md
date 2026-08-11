---
title: AreEqualImpl()
second_title: Aspose.Slides برای مرجع API C++
description: مقایسهٔ برابری اعداد شناور با انواع عددی.
type: docs
weight: 27
url: /fa/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) تابع


مقایسهٔ مساوی اعداد شناور با انواع عددی.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء سمت چپ. |
| T2 | نوع شیء سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1 | مقدار سمت چپ. |
| rhs | const T2 | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع


مقایسهٔ مساوی مقادیر که یکی یا هر دو آن‌ها [Decimal](../../system/decimal/) هستند.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء سمت چپ. |
| T2 | نوع شیء سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1\& | مقدار سمت چپ. |
| rhs | const T2\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع


مقایسهٔ مساوی انواع غیر‌اشاره‌گر با استفاده از روش Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) تابع


مقایسهٔ مساوی انواع غیر‌اشاره‌گر با استفاده از روش Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع


مقایسهٔ مساوی انواع غیر‌اشاره‌گر با استفاده از عملگر == ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T\& | مقدار سمت چپ. |
| rhs | const T\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) تابع


مقایسهٔ مساوی انواع قابل جعبه‌گذاری با مقادیر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T | مقدار سمت چپ. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) تابع


مقایسهٔ مساوی انواع قابل جعبه‌گذاری با مقادیر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت چپ. |
| rhs | T | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) تابع


مقایسهٔ مساوی رشته ثابت با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از استخراج (unboxing).

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const char16_t * | مقدار سمت چپ. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) تابع


مقایسهٔ مساوی رشته ثابت با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از استخراج (unboxing).

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار سمت چپ. |
| rhs | const char16_t * | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) تابع


مقایسهٔ مساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T | مقدار سمت چپ. |
| s | std::nullptr_t | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) تابع


مقایسهٔ مساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| rhs | std::nullptr_t | مقدار سمت راست. |
| s | T | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع


مقایسهٔ مساوی انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1\& | مقدار سمت چپ. |
| rhs | const T2\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع


مقایسهٔ مساوی انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const T1\& | مقدار سمت چپ. |
| rhs | const T2\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) تابع


مقایسهٔ مساوی یک نوع تصادفی با مقدار [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T1 | مقدار سمت چپ. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) تابع


مقایسهٔ مساوی مقدار [Nullable](../../system/nullable/) با یک نوع تصادفی.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | مقدار سمت چپ. |
| rhs | T2 | مقدار سمت راست. |
| s | long long | پارامتر سرویسی که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) تابع


مقایسهٔ مساوی انواع تصادفی با استفاده از الگوریتم‌های gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع سمت چپ. |
| T2 | نوع سمت راست. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت سمت چپ. |
| rhs_expr | const char * | عبارت سمت راست. |
| lhs | T1 | مقدار سمت چپ. |
| rhs | T2 | مقدار سمت راست. |

### مقدار بازگشت

نتیجهٔ ادعای سبک gtest.

## همچنین ببینید

* تعریف‌نوع [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* تعریف‌نوع [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* تعریف‌نوع [SharedPtr](../../system/sharedptr/)
* کلاس [Object](../../system/object/)
* کلاس [Stream](../../system.io/stream/)
* کلاس [Nullable](../../system/nullable/)
* ساختار [IsSmartPtr](../../system/issmartptr/)
* ساختار [IsBoxable](../../system/isboxable/)
* ساختار [IsStringByteSequence](../../system/isstringbytesequence/)
* ساختار [IsNullable](../../system/isnullable/)
* فضای‌نام [System::TestPredicates](../)
* کتابخانه [Aspose.Slides](../../)