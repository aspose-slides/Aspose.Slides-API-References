---
title: operator=()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κάνει μετακίνηση ανάθεσης σε smart pointer.
type: docs
weight: 27
url: /el/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) μέθοδος

Move-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Δείκτης από τον οποίο θα γίνει μετακίνηση ανάθεσης. |

### Τιμή επιστροφής

Αναφορά στον εαυτό.

## DynamicWeakPtr::operator=(const SmartPtr_&) μέθοδος

Copy-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Δείκτης από τον οποίο θα γίνει αντιγραφή ανάθεσης. |

### Τιμή επιστροφής

Αναφορά στον εαυτό.

## DynamicWeakPtr::operator=(const SmartPtr<Q>&) μέθοδος

Copy-assigns smart pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος του προέλευσης pointee. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Δείκτης από τον οποίο θα γίνει αντιγραφή ανάθεσης. |

### Τιμή επιστροφής

Αναφορά στον εαυτό.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) μέθοδος

Assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Τιμή δείκτη. |

### Τιμή επιστροφής

Αναφορά στον εαυτό.

## DynamicWeakPtr::operator=(std::nullptr_t) μέθοδος

Sets smart pointer to null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Τιμή επιστροφής

Αναφορά στον εαυτό.

## Δείτε επίσης

* Τύπος [DynamicWeakPtr_](../dynamicweakptr_/)
* Τύπος [SmartPtr_](../smartptr_/)
* Τύπος [Pointee_](../../smartptr/pointee_/)
* Κλάση [DynamicWeakPtr](../)
* Κλάση [SmartPtr](../../smartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)