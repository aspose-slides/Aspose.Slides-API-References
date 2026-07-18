---
title: AreNotEqualImpl()
second_title: Aspose.Slides για C++ API Αναφορά
description: Η σύγκριση ανισότητας συγκρίνει τιμές, μία ή και οι δύο από τις οποίες είναι Decimal.
type: docs
weight: 53
url: /el/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει τιμές, μία ή και οι δύο από τις οποίες είναι [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει μη-δείκτες χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει μη-δείκτες χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει μη-δείκτες χρησιμοποιώντας τον τελεστή != που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει boxable με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει boxable με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή LHS. |
| rhs | T | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει τυχαίο τύπο με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| s | std::nullptr_t | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) συνάρτηση


Η σύγκριση ανισότητας συγκρίνει τυχαίο τύπο με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος [Object](../../system/object/). |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| rhs | std::nullptr_t | Τιμή RHS. |
| s | T | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Η σύγκριση ισότητας συγκρίνει τύπους δεικτών.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) συνάρτηση


Η σύγκριση ισότητας συγκρίνει τυχαίους τύπους χρησιμοποιώντας αλγορίθμους gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T1 | Τιμή LHS. |
| rhs | T2 | Τιμή RHS. |

### Τιμή Επιστροφής

αποτέλεσμα ελέγχου σε στυλ gtest.

## Δείτε επίσης

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)