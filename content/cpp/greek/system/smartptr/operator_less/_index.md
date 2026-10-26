---
title: operator<()
second_title: Αναφορά API του Aspose.Slides για C++
description: Παρέχει σημασιολογία λιγότερο-σύγκρισης για την κλάση SmartPtr.
type: docs
weight: 235
url: /el/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const μέθοδος


Παρέχει σημασιολογία λιγότερο-σύγκρισης για [SmartPtr](../) κλάση.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| p | Y * | Pointer to compare current one to. |

### Τιμή επιστροφής

Αληθές εάν το αντικείμενο που παραπέμπεται από [SmartPtr](../) είναι 'less' από το p και ψευδές διαφορετικά.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const μέθοδος


Παρέχει σημασιολογία λιγότερο-σύγκρισης για [SmartPtr](../) κλάση.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointer to compare current one to. |

### Τιμή επιστροφής

Αληθές εάν το αντικείμενο που παραπέμπεται από [SmartPtr](../) είναι 'less' από το x και ψευδές διαφορετικά.

## Δείτε επίσης

* Κλάση [SmartPtr](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)