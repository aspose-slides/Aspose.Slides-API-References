---
title: AreNotEqualImpl()
second_title: مرجع API Aspose.Slides للغة C++
description: يقارن عدم التساوي القيم عندما يكون أحدهما أو كلاهما من النوع Decimal.
type: docs
weight: 53
url: /ar/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


يقارن عدم التساوي القيم عندما يكون أحدهما أو كلاهما [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع كائن الجانب الأيسر. |
| T2 | نوع كائن الجانب الأيمن. |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة


يقارن عدم التساوي الأنواع غير المؤشرية باستخدام طريقة Equals المقدمة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) دالة


يقارن عدم التساوي الأنواع غير المؤشرية باستخدام طريقة Equals المقدمة.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) دالة


يقارن عدم التساوي الأنواع غير المؤشرية باستخدام العامل != المقدم.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T\& | قيمة الجانب الأيسر. |
| rhs | const T\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) دالة


يقارن عدم التساوي القابلة للصناديق مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك الصناديق.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T | قيمة الجانب الأيسر. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) دالة


يقارن عدم التساوي القابلة للصناديق مع قيم [SmartPtr](../../system/smartptr/) باستخدام فك الصناديق.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | قيمة الجانب الأيسر. |
| rhs | T | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) دالة


يقارن عدم التساوي نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T | قيمة الجانب الأيسر. |
| s | std::nullptr_t | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) دالة


يقارن عدم التساوي نوعًا عشوائيًا مع nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع [Object](../../system/object/). |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| rhs | std::nullptr_t | قيمة الجانب الأيمن. |
| s | T | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) دالة


يقارن المساواة أنواع المؤشر.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | const T1\& | قيمة الجانب الأيسر. |
| rhs | const T2\& | قيمة الجانب الأيمن. |
| s | long long | معلمة خدمة تُستخدم كمحدد لتطبيق الدالة؛ يتم تجاهل قيمة المعلمة. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) دالة


يقارن المساواة الأنواع العشوائية باستخدام خوارزميات gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع الجانب الأيسر. |
| T2 | نوع الجانب الأيمن. |

### الوسيطات

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الجانب الأيسر. |
| rhs_expr | const char * | تعبير الجانب الأيمن. |
| lhs | T1 | قيمة الجانب الأيسر. |
| rhs | T2 | قيمة الجانب الأيمن. |

### قيمة الإرجاع

نتيجة تأكيد على نمط gtest.

## انظر أيضًا

* تعريف نوع [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* تعريف نوع [SharedPtr](../../system/sharedptr/)
* فئة [Object](../../system/object/)
* هيكل [IsSmartPtr](../../system/issmartptr/)
* هيكل [IsBoxable](../../system/isboxable/)
* مساحة الاسم [System::TestPredicates](../)
* مكتبة [Aspose.Slides](../../)