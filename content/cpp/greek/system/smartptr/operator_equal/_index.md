---
title: operator=()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μεταθέτει αντικείμενο SmartPtr. Το x γίνεται αχρησιμοποίητο.
type: docs
weight: 27
url: /el/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) μέθοδος

Μεταθέτει [SmartPtr](../) αντικείμενο. Το x γίνεται αχρησιμοποίητο.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Δείκτης προς μεταθέσιμο. |

### Τιμή Επιστροφής

Αναφορά σε αυτό το αντικείμενο.

## SmartPtr::operator=(const SmartPtr_\&) μέθοδος

Αντιγράφει-εκχωρεί [SmartPtr](../) αντικείμενο.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Δείκτης προς αντιγραφή-εκχώρηση. |

### Τιμή Επιστροφής

Αναφορά σε αυτό το αντικείμενο.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) μέθοδος

Αντιγράφει-εκχωρεί [SmartPtr](../) αντικείμενο. Εκτελεί τις απαιτούμενες μετατροπές τύπου.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος του αντικειμένου στο οποίο δείχνει το x. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Δείκτης προς αντιγραφή-εκχώρηση. |

### Τιμή Επιστροφής

Αναφορά σε αυτό το αντικείμενο.

## SmartPtr::operator=(Pointee_ *) μέθοδος

Αναθέτει ακατέργαστο δείκτη σε [SmartPtr](../) αντικείμενο.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Τιμή δείκτη προς ανάθεση. |

### Τιμή Επιστροφής

Αναφορά σε αυτό το αντικείμενο.

## SmartPtr::operator=(std::nullptr_t) μέθοδος

Ορίζει την τιμή του δείκτη σε nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Τιμή Επιστροφής

Αναφορά σε αυτό το αντικείμενο.

## Δείτε επίσης

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)