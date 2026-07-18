---
title: AreSameImpl()
second_title: Aspose.Slides για το C++ API
description: Are-same συγκρίνει έξυπνα δείκτες.
type: docs
weight: 79
url: /el/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Are-same συγκρίνει έξυπνα δείκτες.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα έγκρισης σε στυλ gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση


Are-same συγκρίνει εξαιρέσεις.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |
| s | long long | Παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή επιστροφής

αποτέλεσμα έγκρισης σε στυλ gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) συνάρτηση


Are-same συγκρίνει μη-δείκτες τιμές.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου LHS. |
| T2 | Τύπος αντικειμένου RHS. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση LHS. |
| rhs_expr | const char * | Έκφραση RHS. |
| lhs | const T1\& | Τιμή LHS. |
| rhs | const T2\& | Τιμή RHS. |

### Τιμή επιστροφής

αποτέλεσμα έγκρισης σε στυλ gtest.

## Δείτε επίσης

* Δομή [IsSmartPtr](../../system/issmartptr/)
* Δομή [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Χώρος ονομάτων [System::TestPredicates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)