---
title: WeakPtr()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί δείκτη null.
type: docs
weight: 1
url: /el/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) κατασκευαστής

Δημιουργεί δείκτη null.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) κατασκευαστής

Δημιουργεί αδύναμο δείκτη προς το δεδομένο αντικείμενο.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) για τη δημιουργία αδύναμου δείκτη προς. |

## WeakPtr::WeakPtr(const SmartPtr_&) κατασκευαστής

Δημιουργεί αδύναμο δείκτη που αναφέρεται στον ίδιο δείκτη στον οποίο δείχνει το ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Δείκτης για αντιγραφή τιμής του pointee από. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) κατασκευαστής

Δημιουργεί αδύναμο δείκτη που αναφέρεται στον ίδιο δείκτη στον οποίο δείχνει το x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος pointee του πηγαίου δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Δείκτης για αντιγραφή τιμής του pointee από. |

## WeakPtr::WeakPtr(const WeakPtr_&) κατασκευαστής

Δημιουργεί ένα αντίγραφο του αδύναμου δείκτη.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Δείκτης για αντιγραφή τιμής του pointee από. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) κατασκευαστής

Δημιουργεί ένα αντίγραφο του αδύναμου δείκτη.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Q | Τύπος πηγαίου pointee. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Δείκτης για αντιγραφή τιμής του pointee από. |

## WeakPtr::WeakPtr(SmartPtr_&&) κατασκευαστής

Δημιουργεί αδύναμο δείκτη με μετακίνηση.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Δείκτης για μετακίνηση τιμής του pointee από. |

## Δείτε επίσης

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Κλάση [WeakPtr](../)
* Κλάση [SmartPtr](../../smartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)