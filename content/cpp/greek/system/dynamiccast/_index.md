---
title: DynamicCast()
second_title: Aspose.Slides για C++ API Reference
description: Εκτελεί δυναμική μετατροπή σε αντικείμενα Exception.
type: docs
weight: 2497
url: /el/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) συνάρτηση

Εκτελεί δυναμική μετατροπή (cast) σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος Exception στόχου. |
| TFrom | Τύπος Exception πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const TFrom\& | Δείκτης πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί δυναμική μετατροπή σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος pointee στόχου. |
| TFrom | Τύπος pointee πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Δείκτης πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(SmartPtr\<TFrom\>) συνάρτηση

Αποσυσκευάζει enum με κουβά μέσω μετατροπής.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος enum στόχου. |
| TFrom | Τύπος pointee πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Δείκτης στο αντικείμενο από το οποίο αποσυσκευάζονται τα δεδομένα. |

### Τιμή επιστροφής

Αποσυσκευασμένη τιμή enum.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(std::nullptr_t) συνάρτηση

Εκτελεί δυναμική μετατροπή (cast) μηδενικών αντικειμένων.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος pointee στόχου. |

### Τιμή επιστροφής

nullptr.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(TFrom\&) συνάρτηση

Εκτελεί δυναμική μετατροπή σε αντικείμενα μη-δείκτη.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος στόχου. |
| TFrom | Τύπος πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | TFrom\& | Αντικείμενο πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(SmartPtr\<TFrom\>) συνάρτηση

Εκτελεί δυναμική μετατροπή σε Objects σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος Exception στόχου. |
| TFrom | Τύπος [Object](../object/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Δείκτης πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::DynamicCast(TFrom) συνάρτηση

Εκτελεί δυναμική μετατροπή από IntPtr σε δείκτη.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος στόχου. |
| TFrom | Τύπος πηγής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | TFrom | Τιμή IntPtr πηγής. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής.

Παρατηρημένο
:   Απομένει για συμβατότητα με παλαιότερους κώδικες. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Κλάση [Object](../object/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Δομή [CastResult](../castresult/)
* Δομή [IsSmartPtr](../issmartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)