---
title: AreEqualImpl()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقارن للمساواة القيم العائمة مع الأنواع العددية.
type: docs
weight: 27
url: /ar/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) دالة

يقارن للمساواة القيم العائمة مع الأنواع العددية.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن LHS. |
| T2 | نوع الكائن RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1 | قيمة LHS. |
| rhs | const T2 | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة

يقارن للمساواة القيم حيث يكون أحدهما أو كلاهما [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن LHS. |
| T2 | نوع الكائن RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة

يقارن للمساواة الأنواع غير المؤشرة باستخدام طريقة Equals المتوفرة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T\& | قيمة LHS. |
| rhs | const T\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) دالة

يقارن للمساواة الأنواع غير المؤشرة باستخدام طريقة Equals المتوفرة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T\& | قيمة LHS. |
| rhs | const T\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة

يقارن للمساواة الأنواع غير المؤشرة باستخدام المشغل == المتوفر.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T\& | قيمة LHS. |
| rhs | const T\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) دالة

يقارن للمساواة القابل للتغليف مع قيم [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T | قيمة LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) دالة

يقارن للمساواة القابل للتغليف مع قيم [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة LHS. |
| rhs | T | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) دالة

يقارن للمساواة حرفية سلسلة مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك التغليف.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const char16_t * | قيمة LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) دالة

يقارن للمساواة حرفية سلسلة مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك التغليف.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة LHS. |
| rhs | const char16_t * | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) دالة

يقارن للمساواة نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T | قيمة LHS. |
| s | std::nullptr_t | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) دالة

يقارن للمساواة نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| rhs | std::nullptr_t | قيمة RHS. |
| s | T | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة

يقارن للمساواة أنواع المؤشرات.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة

يقارن للمساواة أنواع المؤشرات.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T1\& | قيمة LHS. |
| rhs | const T2\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) دالة

يقارن للمساواة نوعًا عشوائيًا مع قيمة [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1 | قيمة LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) دالة

يقارن للمساواة قيمة [Nullable](../../system/nullable/) مع نوع عشوائي.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | قيمة LHS. |
| rhs | T2 | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) دالة

يقارن للمساواة الأنواع العشوائية باستخدام خوارزميات gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع LHS. |
| T2 | نوع RHS. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | T1 | قيمة LHS. |
| rhs | T2 | قيمة RHS. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة

يقارن للمساواة قيمتين من [System::String](../../system/string/)، مع تجنب استدعاء دالة عضو على [String](../../system/string/) فارغ. القالب (بدلاً من التحميل البسيط الذي يأخذ const [String](../../system/string/)&) يسمح باستدعاءات مختلطة الأنواع – مثل مقارنة حرفية سلسلة char16_t مع [String](../../system/string/) – لتفشل في استنتاج T واحد متسق وتُستبعد من هذا المرشح تمامًا، بدلاً من التنافس مع القالب العام AreEqualImpl<T1,T2> عبر مُحدد المعامل طويل/int وإنتاج تعارض في حل التحميل.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/)، مقيد بـ [System::String](../../system/string/). |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير LHS. |
| rhs_expr | const char * | تعبير RHS. |
| lhs | const T\& | قيمة LHS. |
| rhs | const T\& | قيمة RHS. |
| s | long long | معامل خدمة يُستخدم كمحدد لتنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضًا

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* فئة [String](../../system/string/)
* فئة [Object](../../system/object/)
* فئة [Stream](../../system.io/stream/)
* فئة [Nullable](../../system/nullable/)
* بنية [IsSmartPtr](../../system/issmartptr/)
* بنية [IsBoxable](../../system/isboxable/)
* بنية [IsStringByteSequence](../../system/isstringbytesequence/)
* بنية [IsNullable](../../system/isnullable/)
* نطاق [System::TestPredicates](../)
* مكتبة [Aspose.Slides](../../)