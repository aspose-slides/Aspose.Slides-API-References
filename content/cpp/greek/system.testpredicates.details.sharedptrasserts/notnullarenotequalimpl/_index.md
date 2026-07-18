---
title: NotNullAreNotEqualImpl()
second_title: Αναφορά API Aspose.Slides για C++
description: Η σύγκριση ανισότητας συγκρίνει πίνακες ή λίστες.
type: docs
weight: 105
url: /el/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση

Η σύγκριση ανισότητας συγκρίνει πίνακες ή λίστες.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δοχείου αριστεράς πλευράς. |
| T2 | Τύπος δοχείου δεξιάς πλευράς. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση αριστεράς πλευράς. |
| rhs_expr | const char * | Έκφραση δεξιάς πλευράς. |
| lhs | const T1\& | Τιμή αριστεράς πλευράς. |
| rhs | const T2\& | Τιμή δεξιάς πλευράς. |
| s | long long | Παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

Αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) συνάρτηση

Η σύγκριση ανισότητας συγκρίνει παραδείγματα IEnumerable.

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος στοιχείου αριστεράς πλευράς. |
| T2 | Τύπος στοιχείου δεξιάς πλευράς. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση αριστεράς πλευράς. |
| rhs_expr | const char * | Έκφραση δεξιάς πλευράς. |
| lhs | const T1\& | Τιμή αριστεράς πλευράς. |
| rhs | const T2\& | Τιμή δεξιάς πλευράς. |
| s | long long | Παράμετρος υπηρεσίας που λειτουργεί ως επιλογέας της υλοποίησης της συνάρτησης· η τιμή της παραμέτρου αγνοείται |

### Τιμή Επιστροφής

Αποτέλεσμα ελέγχου σε στυλ gtest.

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) συνάρτηση

Η σύγκριση ανισότητας συγκρίνει άγνωστους τύπους χρησιμοποιώντας τη μέθοδο Eqauals.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος αντικειμένου αριστεράς πλευράς. |
| T2 | Τύπος αντικειμένου δεξιάς πλευράς. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs_expr | const char * | Έκφραση αριστεράς πλευράς. |
| rhs_expr | const char * | Έκφραση δεξιάς πλευράς. |
| lhs | const T1\& | Τιμή αριστεράς πλευράς. |
| rhs | const T2\& | Τιμή δεξιάς πλευράς. |

### Τιμή Επιστροφής

Αποτέλεσμα ελέγχου σε στυλ gtest.

## Δείτε επίσης

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)