---
title: AreEqualData()
second_title: Aspose.Slides για την αναφορά API του C++
description: "Συγκρίνει ισότιμα δύο containers χρησιμοποιώντας System::Object::Equals στα στοιχεία. Λειτουργεί για στοιχεία SmartPtr."
type: docs
weight: 14
url: /el/system.testpredicates.details.sharedptrasserts/areequaldata/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Συγκρίνει ισότιμα δύο containers χρησιμοποιώντας [System::Object::Equals](../../system/object/equals/) στα στοιχεία. Λειτουργεί για [SmartPtr](../../system/smartptr/) στοιχεία.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος container LHS. |
| T2 | Τύπος container RHS. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | const T1\& | Αναφορά σε container LHS. |
| rhs | const T2\& | Αναφορά σε container RHS. |

### Return Value

Αληθές εάν τα περιεχόμενα στοιχεία και οι διαστάσεις ταιριάζουν, ψευδές αλλιώς.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1\&, const T2\&) function


Συγκρίνει ισότιμα δύο containers χρησιμοποιώντας τον τελεστή == στα στοιχεία. Λειτουργεί για στοιχεία που δεν είναι SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T1 &lhs, const T2 &rhs)
```


### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος container LHS. |
| T2 | Τύπος container RHS. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | const T1\& | Container LHS. |
| rhs | const T2\& | Container RHS. |

### Return Value

Αληθές εάν τα περιεχόμενα στοιχεία και οι διαστάσεις ταιριάζουν, ψευδές αλλιώς.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T\&, const T\&) function


Συγκρίνει ισότιμα δύο containers του ίδιου τύπου. Λειτουργεί για στοιχεία που δεν είναι SmartPtr.

```cpp
template<typename T> std::enable_if<!System::IsSmartPtr<typenameT::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualData(const T &lhs, const T &rhs)
```


### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος container LHS. |
| T2 | Τύπος container RHS. |

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | const T\& | Container LHS. |
| rhs | const T\& | Container RHS. |

### Return Value

Αληθές εάν τα περιεχόμενα στοιχεία και οι διαστάσεις ταιριάζουν, ψευδές αλλιώς.

## Δείτε επίσης

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)