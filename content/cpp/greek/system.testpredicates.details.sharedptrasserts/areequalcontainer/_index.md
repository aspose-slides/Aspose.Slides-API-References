---
title: AreEqualContainer()
second_title: Aspose.Slides για το API του C++
description: Συγκρίνει ισοδύναμα δύο containers χρησιμοποιώντας operator == στα στοιχεία. Λειτουργεί για στοιχεία που δεν είναι SmartPtr.
type: docs
weight: 1
url: /el/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) συνάρτηση


Ισοδυναμικά συγκρίνει δύο containers χρησιμοποιώντας operator == στα στοιχεία. Λειτουργεί για στοιχεία που δεν είναι SmartPtr.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος container αριστερά. |
| T2 | Τύπος container δεξιά. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Container αριστερά. |
| rhs | const T2\& | Container δεξιά. |

### Τιμή επιστροφής

Αληθές εάν τα στοιχεία και τα μεγέθη που περιέχονται ταιριάζουν, ψευδές διαφορετικά.

## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) συνάρτηση


Ισοδυναμικά συγκρίνει δύο containers χρησιμοποιώντας [System::Object::Equals](../../system/object/equals/) στα στοιχεία. Λειτουργεί για στοιχεία [SmartPtr](../../system/smartptr/).

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Τύπος container αριστερά. |
| T2 | Τύπος container δεξιά. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | Αναφορά σε container αριστερά. |
| rhs | const T2\& | Αναφορά σε container δεξιά. |

### Τιμή επιστροφής

Αληθές εάν τα στοιχεία και τα μεγέθη που περιέχονται ταιριάζουν, ψευδές διαφορετικά.

## Δείτε επίσης

* Δομή [IsSmartPtr](../../system/issmartptr/)
* Χώρος ονομάτων [System::TestPredicates::Details::SharedPtrAsserts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)