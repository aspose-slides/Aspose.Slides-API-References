---
title: AreNotEqualImpl()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مقارنة عدم المساواة تقارن القيم حيث يكون أحدهما أو كلاهما Decimal.
type: docs
weight: 53
url: /ar/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


مقارنة عدم المساواة تقارن القيم حيث تكون واحدة أو كلتاهما [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الكائن على الطرف الأيسر. |
| T2 | نوع الكائن على الطرف الأيمن. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const T1\& | قيمة الطرف الأيسر. |
| rhs | const T2\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة


مقارنة عدم المساواة تقارن قيمتين [System::String](../../system/string/)، مع الحماية من استدعاء دالة عضو على [String](../../system/string/) فارغ. تم إنشاء القالب لنفس أسباب الاستثناء المستندة إلى الاستنتاج كما في نسخة AreEqualImpl [String](../../system/string/) أعلاه.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/)، مقيد بـ [System::String](../../system/string/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const T\& | قيمة الطرف الأيسر. |
| rhs | const T\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة


مقارنة عدم المساواة تقارن الأنواع غير المؤشرية باستخدام طريقة Equals المتوفرة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const T\& | قيمة الطرف الأيسر. |
| rhs | const T\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) دالة


مقارنة عدم المساواة تقارن الأنواع غير المؤشرية باستخدام طريقة Equals المتوفرة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | T\& | قيمة الطرف الأيسر. |
| rhs | const T\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة


مقارنة عدم المساواة تقارن الأنواع غير المؤشرية باستخدام عامل != المتوفر.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const T\& | قيمة الطرف الأيسر. |
| rhs | const T\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) دالة


مقارنة عدم المساواة تقارن القابلة للتعبئة مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك الصندوق.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | T | قيمة الطرف الأيسر. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) دالة


مقارنة عدم المساواة تقارن القابلة للتعبئة مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك الصندوق.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الطرف الأيسر. |
| rhs | T | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) دالة


مقارنة عدم المساواة تقارن نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | T | قيمة الطرف الأيسر. |
| s | std::nullptr_t | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) دالة


مقارنة عدم المساواة تقارن نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| rhs | std::nullptr_t | قيمة الطرف الأيمن. |
| s | T | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


مقارنة المساواة تقارن الأنواع المؤشرية.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الطرف الأيسر. |
| T2 | نوع الطرف الأيمن. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | const T1\& | قيمة الطرف الأيسر. |
| rhs | const T2\& | قيمة الطرف الأيمن. |
| s | long long | معامل خدمة يُستخدم كاختيار لتحديد تنفيذ الدالة؛ يتم تجاهل قيمة المعامل. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) دالة


مقارنة المساواة تقارن الأنواع العشوائية باستخدام خوارزميات gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع الطرف الأيسر. |
| T2 | نوع الطرف الأيمن. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| lhs | T1 | قيمة الطرف الأيسر. |
| rhs | T2 | قيمة الطرف الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد بنمط gtest.

## انظر أيضًا

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)