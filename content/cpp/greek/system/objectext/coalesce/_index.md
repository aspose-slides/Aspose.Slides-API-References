---
title: Coalesce()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Υλοποίηση της μετάφρασης του τελεστή '??' για μη-μηδενικούς τύπους.
type: docs
weight: 170
url: /el/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) μέθοδος


Υλοποίηση της μετάφρασης του τελεστή '??' για μη-μηδενικούς τύπους.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T0 | Τύπος τιμής LHS. |
| T1 | Τύπος της συνάρτησης lambda που περιβάλλει την έκφραση RHS. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0 | Τιμή LHS. |
| func | T1 | Έκφραση RHS. |

### Τιμή επιστροφής

Εάν η τιμή LHS δεν είναι μηδενική, επιστρέφει LHS, διαφορετικά υπολογίζει την έκφραση RHS και επιστρέφει το αποτέλεσμα.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) μέθοδος


Υλοποίηση της μετάφρασης του τελεστή '??' για μηδενικούς τύπους.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T0 | Τύπος τιμής LHS. |
| T1 | Τύπος της συνάρτησης lambda που περιβάλλει την έκφραση RHS. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Τιμή LHS. |
| func | T1 | Έκφραση RHS. |

### Τιμή επιστροφής

Εάν η τιμή LHS δεν είναι μηδενική, επιστρέφει LHS, διαφορετικά υπολογίζει την έκφραση RHS και επιστρέφει το αποτέλεσμα.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Κλάση [Nullable](../../nullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)