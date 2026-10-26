---
title: GetType()
second_title: Αναφορά API του Aspose.Slides για C++
description: Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για έξυπνους δείκτες.
type: docs
weight: 1
url: /el/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για έξυπνους δείκτες.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος αντικειμένου δείκτη. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) για λήψη [TypeInfo](../../typeinfo/). |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει την τελική κλάση του αντικειμένου που περάστηκε.

## ObjectType::GetType(const T\&) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για δομές.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος δομής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) για λήψη [TypeInfo](../../typeinfo/). |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει την τελική κλάση του αντικειμένου που περάστηκε.

## ObjectType::GetType(const T\&) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για εξαιρέσεις.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος εξαίρεσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) για λήψη [TypeInfo](../../typeinfo/). |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει την τελική κλάση του αντικειμένου που περάστηκε.

## ObjectType::GetType(const T) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για απλούς τύπους.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T | IGNORED |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τον τύπο του αντικειμένου που περάστηκε.

## ObjectType::GetType(const T) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για [Nullable](../../nullable/) τύπους.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Nullable](../../nullable/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T | IGNORED |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τον τύπο του αντικειμένου που περάστηκε.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για απλούς τύπους.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τον ορισμένο τύπο.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για τύπους enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τον ορισμένο τύπο.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για δομές και δείκτες.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τη δομή που ορίζεται.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Nullable](../../nullable/) τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τη δομή που ορίζεται.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | MutlicastDelegate τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τη δομή που ορίζεται.

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για δομές και δείκτες.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τη δομή που ορίζεται ή τύπο του δείκτη αν κληθεί για [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για τύπο string.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Απλός τύπος. |

### Τιμή επιστροφής

Αναφορά const στο [TypeInfo](../../typeinfo/) δομή που περιγράφει τον τύπο [String](../../string/).

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() μέθοδος


Υλοποιεί τη μετάφραση typeof(). Υπερφόρτωση για [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Δείτε επίσης

* Κλάση [ObjectType](../)
* Κλάση [TypeInfo](../../typeinfo/)
* Κλάση [String](../../string/)
* Δομή [IsSmartPtr](../../issmartptr/)
* Δομή [IsExceptionWrapper](../../isexceptionwrapper/)
* Δομή [IsNullable](../../isnullable/)
* Δομή [IsBoxable](../../isboxable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)