---
title: CoalesceAssign()
second_title: Aspose.Slides για C++ Αναφορά API
description: Υλοποίηση της μετάφρασης του τελεστή '??='.
type: docs
weight: 183
url: /el/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) μέθοδος


Υλοποίηση της μετάφρασης του τελεστή '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T0\& | LHS value. |
| func | T1 | RHS expression. |

### Τιμή επιστροφής

Εάν η τιμή LHS δεν είναι null, επιστρέφει το LHS, διαφορετικά υπολογίζει την έκφραση RHS και επιστρέφει το αποτέλεσμα.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)