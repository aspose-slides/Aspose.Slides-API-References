---
title: Box()
second_title: Αναφορά API του Aspose.Slides για C++
description: Συσκευάζει τύπους τιμών για μετατροπή σε Object. Υλοποίηση για τύπους enum.
type: docs
weight: 40
url: /el/system/objectext/box/
---
## ObjectExt::Box(const T\&) μέθοδος


Συσκευάζει τιμές τύπων για μετατροπή σε [Object](../../object/). Υλοποίηση για τύπους enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Enum](../../enum/) τύπος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) τιμή για συσκευασία. |

### Τιμή επιστροφής

Έξυπνος δείκτης σε αντικείμενο που διατηρεί τη συσκευασμένη τιμή.

## ObjectExt::Box(const T\&) μέθοδος


Συσκευάζει τιμές τύπων για μετατροπή σε [Object](../../object/). Υλοποίηση για μη-enum τύπους.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | Τιμή για συσκευασία. |

### Τιμή επιστροφής

Έξυπνος δείκτης σε αντικείμενο που διατηρεί τη συσκευασμένη τιμή.

## ObjectExt::Box(const T\&) μέθοδος


Συσκευάζει τύπους [Nullable](../../nullable/) για μετατροπή σε [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | Τιμή για συσκευασία. |

### Τιμή επιστροφής

Έξυπνος δείκτης σε αντικείμενο που διατηρεί τη συσκευασμένη τιμή.

## ObjectExt::Box(const String\&) μέθοδος


Συσκευάζει τιμές συμβολοσειράς.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Τιμή για συσκευασία. |

### Τιμή επιστροφής

Συσκευασμένη τιμή ή null, εάν η πηγή συμβολοσειράς είναι null.

## Δείτε επίσης

* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [Object](../../object/)
* Κλάση [ObjectExt](../)
* Κλάση [String](../../string/)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)