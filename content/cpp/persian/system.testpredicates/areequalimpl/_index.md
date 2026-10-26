---
title: AreEqualImpl()
second_title: Aspose.Slides برای مرجع API C++
description: مقایسه برابر برای اعداد ممیز شناور با انواع عددی.
type: docs
weight: 27
url: /fa/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) تابع

مقایسه برابر برای اعداد شناور با انواع عددی.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1 | مقدار LHS. |
| rhs | const T2 | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع

مقایسه برابر برای مقادیری که یکی یا هر دو آن‌ها [Decimal](../../system/decimal/) هستند.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع شیء LHS. |
| T2 | نوع شیء RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع

مقایسه برابر برای انواع غیر اشاره‌گر با استفاده از متد Equals فراهم‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T\& | مقدار LHS. |
| rhs | const T\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) تابع

مقایسه برابر برای انواع غیر اشاره‌گر با استفاده از متد Equals فراهم‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T\& | مقدار LHS. |
| rhs | const T\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع

مقایسه برابر برای انواع غیر اشاره‌گر با استفاده از عملگر == فراهم‌شده.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T\& | مقدار LHS. |
| rhs | const T\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) تابع

مقایسه برابر برای شیء قابل جعبه‌سازی با مقادیر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T | مقدار LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) تابع

مقایسه برابر برای شیء قابل جعبه‌سازی با مقادیر [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار LHS. |
| rhs | T | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) تابع

مقایسه برابر برای مقدار متنی ثابت با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از باز کردن جعبه.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const char16_t * | مقدار LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) تابع

مقایسه برابر برای مقدار متنی ثابت با مقادیر [SmartPtr](../../system/smartptr/) با استفاده از باز کردن جعبه.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | مقدار LHS. |
| rhs | const char16_t * | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) تابع

مقایسه برابر برای نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T | مقدار LHS. |
| s | std::nullptr_t | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) تابع

مقایسه برابر برای نوع تصادفی با nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| rhs | std::nullptr_t | مقدار RHS. |
| s | T | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع

مقایسه برابر برای انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) تابع

مقایسه برابر برای انواع اشاره‌گر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T1\& | مقدار LHS. |
| rhs | const T2\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) تابع

مقایسه برابر برای نوع تصادفی با مقدار [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T1 | مقدار LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) تابع

مقایسه برابر برای مقدار [Nullable](../../system/nullable/) با نوع تصادفی.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | مقدار LHS. |
| rhs | T2 | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) تابع

مقایسه برابر برای انواع تصادفی با استفاده از الگوریتم‌های gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | T1 | مقدار LHS. |
| rhs | T2 | مقدار RHS. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) تابع

مقایسه برابر برای دو مقدار [System::String](../../system/string/)، به‌گونه‌ای که از فراخوانی یک تابع عضو روی [String](../../system/string/) خالی جلوگیری شود. قالب‌دار (نه یک بارگذاری ساده که const [String](../../system/string/)& می‌گیرد) تا فراخوانی‌های ترکیبی-نوع-دار—مثلاً یک مقدار ثابت رشته‌ای char16_t در مقابل [String](../../system/string/)—نتوانند یک T سازگار استخراج کنند و بنابراین به‌طور کامل از این کاندیدات حذف شوند؛ در عوض به‌جای رقابت با قالب کلی AreEqualImpl<T1,T2> از طریق پارامتر انتخاب‌کنندهٔ long long/int استفاده می‌شود.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع [Object](../../system/object/)، محدود به [System::String](../../system/string/). |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lhs_expr | const char * | عبارت LHS. |
| rhs_expr | const char * | عبارت RHS. |
| lhs | const T\& | مقدار LHS. |
| rhs | const T\& | مقدار RHS. |
| s | long long | یک پارامتر سرویس که به عنوان انتخاب‌کنندهٔ پیاده‌سازی تابع عمل می‌کند؛ مقدار این پارامتر نادیده گرفته می‌شود. |

### مقدار بازگشت

نتیجهٔ ادعای gtest-styled.

## مشاهده نیز

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)