---
title: StaticCast()
second_title: Αναφορά API Aspose.Slides για C++
description: Εκτελεί στατική μετατροπή σε αντικείμενα SmartPtr.
type: docs
weight: 2523
url: /el/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί στατική μετατροπή στα αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος του δείκτη προορισμού. |
| TFrom | Τύπος του δείκτη προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::StaticCast(WeakPtr\<TFrom\> const\&) συνάρτηση

Εκτελεί στατική μετατροπή στα αντικείμενα [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος του δείκτη προορισμού. |
| TFrom | Τύπος του δείκτη προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::StaticCast(std::nullptr_t) συνάρτηση

Εκτελεί στατική μετατροπή μηδενικών αντικειμένων.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος του δείκτη προορισμού. |

### Τιμή επιστροφής

nullptr.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::StaticCast(TFrom) συνάρτηση

Ειδική υλοποίηση για αριθμητικούς τύπους.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) συνάρτηση

Διεξάγει μετατροπή από [String](../string/) σε [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) συνάρτηση

Ειδική υλοποίηση για αριθμητικούς τύπους.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) συνάρτηση

Εκτελεί στατική μετατροπή σε αντικείμενα που δεν είναι δείκτες.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος στόχου. |
| TFrom | Τύπος προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const TFrom\& | Αντικείμενο προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::StaticCast(const TFrom\&) συνάρτηση

Εκτελεί στατική μετατροπή σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος Exception-στόχου. |
| TFrom | Τύπος Exception-προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const TFrom\& | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## System::StaticCast(SmartPtr\<TFrom\>) συνάρτηση

Εκτελεί στατική μετατροπή αντικειμένων σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TTo | Τύπος Exception-στόχου. |
| TFrom | [Object](../object/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Δείκτης προέλευσης. |

### Τιμή επιστροφής

Αποτέλεσμα μετατροπής εάν η μετατροπή επιτρέπεται.

Αποσυρμένο
:   Παραμένει για συμβατότητα με προηγούμενες εκδόσεις. Χρησιμοποιήστε το ExplicitCast αντ' αυτού.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Κλάση [WeakPtr](../weakptr/)
* Κλάση [String](../string/)
* Κλάση [Object](../object/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Δομή [CastResult](../castresult/)
* Δομή [IsSmartPtr](../issmartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)