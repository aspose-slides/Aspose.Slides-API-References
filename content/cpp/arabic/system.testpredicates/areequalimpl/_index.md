---
title: AreEqualImpl()
second_title: مرجع API Aspose.Slides للغة C++
description: يقارن القيم العائمة مع الأنواع الحسابية.
type: docs
weight: 27
url: /ar/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

يقارن القيم العائمة مع الأنواع العددية.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن على الجانب الأيسر. |
| T2 | نوع الكائن على الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1 | قيمة الجانب الأيسر. |
| rhs | const T2 | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

يقارن القيم متساوية عندما يكون أحدهما أو كلاهما [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن على الجانب الأيسر. |
| T2 | نوع الكائن على الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

يقارن القيم المتساوية للأنواع غير المؤشرية باستخدام طريقة Equals المقدمة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) function

يقارن القيم المتساوية للأنواع غير المؤشرية باستخدام طريقة Equals المقدمة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

يقارن الأنواع غير المؤشرية باستخدام العامل == المقدم.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

يقارن القيم القابلة للتعبئة مع قيم [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T | قيمة الجانب الأيسر. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

يقارن القيم القابلة للتعبئة مع قيم [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيسر. |
| rhs | T | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) function

يقارن النص الحرفي مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك التغليف.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const char16_t * | قيمة الجانب الأيسر. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) function

يقارن النص الحرفي مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك التغليف.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيسر. |
| rhs | const char16_t * | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

يقارن نوعًا عشوائيًا بـ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T | قيمة الجانب الأيسر. |
| s | std::nullptr_t | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

يقارن نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| rhs | std::nullptr_t | قيمة الجانب الأيمن. |
| s | T | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

يقارن الأنواع المؤشرة.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

يقارن الأنواع المؤشرة.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) function

يقارن نوعًا عشوائيًا مع قيمة [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T1 | قيمة الجانب الأيسر. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) function

يقارن قيمة [Nullable](../../system/nullable/) مع نوع عشوائي.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | قيمة الجانب الأيسر. |
| rhs | T2 | قيمة الجانب الأيمن. |
| s | long long | معامل خدمة يُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

يقارن الأنواع العشوائية باستخدام خوارزميات gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### المُعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T1 | قيمة الجانب الأيسر. |
| rhs | T2 | قيمة الجانب الأيمن. |

### قيمة الإرجاع

gtest-styled assertion result.

## انظر أيضًا

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)