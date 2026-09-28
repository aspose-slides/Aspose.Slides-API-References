---
title: AreNotEqualImpl()
second_title: Αναφορά API του Aspose.Slides για C++
description: Η σύγκριση ανίσωσης συγκρίνει τιμές, μία ή και οι δύο από τις οποίες είναι Decimal.
type: docs
weight: 53
url: /el/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τιμές, μία ή και οι δύο από τις οποίες είναι [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει δύο τιμές [System::String](../../system/string/), προστατεύοντας ενάντια στην κλήση μεθόδου μέλους σε ένα null [String](../../system/string/). Προτυποποιημένο για τους ίδιους λόγους εξαίρεσης βασισμένους στην παρακράτηση όπως η παραπάνω υπερφόρτωση AreEqualImpl [String](../../system/string/).

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος, περιορισμένος σε [System::String](../../system/string/). |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τύπους που δεν είναι δείκτες χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τύπους που δεν είναι δείκτες χρησιμοποιώντας τη μέθοδο Equals που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τύπους που δεν είναι δείκτες χρησιμοποιώντας τον τελεστή != που παρέχεται.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T\& | Τιμή LHS. |
| rhs | const T\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει αντικείμενα που μπορούν να τοποθετηθούν σε κουτί με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας απο-εμφωλευση.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει αντικείμενα που μπορούν να τοποθετηθούν σε κουτί με τιμές [SmartPtr](../../system/smartptr/) χρησιμοποιώντας απο-εμφωλευση.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Τιμή LHS. |
| rhs | T | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τυχαίο τύπο με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T | Τιμή LHS. |
| s | std::nullptr_t | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) συνάρτηση


Η σύγκριση ανίσωσης συγκρίνει τυχαίο τύπο με nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../system/object/) τύπος. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| rhs | std::nullptr_t | Τιμή nullptr. |
| s | T | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Η σύγκριση ισότητας συγκρίνει τύπους δεικτών.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Μια παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) συνάρτηση


Η σύγκριση ισότητας συγκρίνει τυχαίους τύπους χρησιμοποιώντας αλγόριθμους gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος LHS. |
| T2 | Τύπος RHS. |

### Παράμετρα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | T1 | Τιμή LHS. |
| rhs | T2 | Τιμή RHS. |

### Τιμή επιστροφής

αποτέλεσμα επιβεβαίωσης μορφής gtest.

## Δείτε επίσης

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Κλάση [String](../../system/string/)
* Κλάση [Object](../../system/object/)
* Δομή [IsSmartPtr](../../system/issmartptr/)
* Δομή [IsBoxable](../../system/isboxable/)
* Χώρος ονομάτων [System::TestPredicates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)