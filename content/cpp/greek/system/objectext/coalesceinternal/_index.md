---
title: CoalesceInternal()
second_title: Aspose.Slides για την Αναφορά API C++
description: Υλοποίηση της μετάφρασης του τελεστή '??' για τύπους που δεν επιτρέπουν null. Υπέρφορτωση για την περίπτωση εάν το RT2 είναι μετατρέψιμο σε RT1.
type: docs
weight: 157
url: /el/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) μέθοδος

Υλοποίηση της μετάφρασης του τελεστή '??' για τύπους που δεν είναι nullable. Υπέρφορτωση για την περίπτωση εάν το RT2 είναι μετατρέψιμο σε RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T0 | Τύπος τιμής LHS. |
| T1 | Τύπος της lambda που ενσωματώνει την έκφραση RHS. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | RT1 | Τιμή LHS. |
| func | F | Έκφραση RHS. |

### Τιμή Επιστροφής

Εάν η τιμή LHS δεν είναι null, επιστρέφει το LHS, διαφορετικά υπολογίζει την έκφραση RHS και επιστρέφει το αποτέλεσμα.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)