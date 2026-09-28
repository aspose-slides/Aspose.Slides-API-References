---
title: AreNotEqualImpl()
second_title: مرجع API Aspose.Slides برای C++
description: مقایسه نامساوی مقادیر که یکی یا هر دو آنها Decimal هستند.
type: docs
weight: 53
url: /fa/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

مقایسه نامساوی مقادیر زمانی که یکی یا هر دو آن‌ها [Decimal](../../system/decimal/) هستند.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

مقایسه نامساوی دو مقدار [System::String](../../system/string/)، با جلوگیری از فراخوانی تابع عضو روی یک [String](../../system/string/) تهی. قالب‌بندی شده برای همان دلایل حذف مبتنی بر استنتاج مانند بارگذاری AreEqualImpl [String](../../system/string/) بالا.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

مقایسه نامساوی انواع غیرنقطه‌ای با استفاده از روش Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

مقایسه نامساوی انواع غیرنقطه‌ای با استفاده از روش Equals ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

مقایسه نامساوی انواع غیرنقطه‌ای با استفاده از عملگر != ارائه‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

مقایسه نامساوی نوع قابل جعبه‌گیری با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از بازجعبه‌سازی.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

مقایسه نامساوی نوع قابل جعبه‌گیری با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از بازجعبه‌سازی.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

مقایسه نامساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

مقایسه نامساوی نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T | [Object](../../system/object/) type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

مقایسه مساوی انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | یک پارامتر سرویس که به عنوان انتخابگر پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

مقایسه مساوی انواع تصادفی با استفاده از الگوریتم‌های gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### پارامترهای قالب

| پارامتر | توضیحات |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### مقدار بازگشت

نتیجه‌ی ادعا به سبک gtest.

## همچنین ببینید

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* کلاس [String](../../system/string/)
* کلاس [Object](../../system/object/)
* ساختار [IsSmartPtr](../../system/issmartptr/)
* ساختار [IsBoxable](../../system/isboxable/)
* فضای‌نام [System::TestPredicates](../)
* Library [Aspose.Slides](../../)