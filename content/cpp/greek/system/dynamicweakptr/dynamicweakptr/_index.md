---
title: DynamicWeakPtr()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί μηδενικό έξυπνο δείκτη.
type: docs
weight: 1
url: /el/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) κατασκευαστής

Δημιουργεί μηδενικό έξυπνο δείκτη.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) κατασκευαστής

Δημιουργεί έξυπνο δείκτη που δείχνει στο δοσμένο αντικείμενο.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_&) κατασκευαστής

Δημιουργεί έξυπνο δείκτη με αντιγραφή.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Έξυπνος δείκτης από τον οποίο αντιγράφεται η πληροφορία του pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) κατασκευαστής

Δημιουργεί έξυπνο δείκτη με αντιγραφή.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος pointee του πηγαίου δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Έξυπνος δείκτης από τον οποίο αντιγράφεται η πληροφορία του pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_&) κατασκευαστής

Δημιουργεί έξυπνο δείκτη με αντιγραφή.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Έξυπνος δείκτης από τον οποίο αντιγράφεται η πληροφορία του pointee. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_&&) κατασκευαστής

Δημιουργεί έξυπνο δείκτη με μετακίνηση.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Έξυπνος δείκτης από τον οποίο μετακινείται η πληροφορία του pointee. Καθίσταται μη χρησιμοποιήσιμος μετά την κλήση. |

## Δείτε επίσης

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Κλάση [DynamicWeakPtr](../)
* Κλάση [SmartPtr](../../smartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)