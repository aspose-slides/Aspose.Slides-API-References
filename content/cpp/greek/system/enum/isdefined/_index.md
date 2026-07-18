---
title: IsDefined()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν η καθορισμένη τιμή είναι μέλος του τύπου απαρίθμησης E.
type: docs
weight: 27
url: /el/system/enum/isdefined/
---
## Enum::IsDefined(E) μέθοδος


Καθορίζει εάν η συγκεκριμένη τιμή είναι μέλος του τύπου απαρίθμησης **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | E | Η τιμή που θα ελεγχθεί |

### Τιμή Επιστροφής

Αληθές εάν **value** είναι μέλος της απαρίθμησης **E**, διαφορετικά - ψευδές

## Enum::IsDefined(T) μέθοδος


Καθορίζει εάν η συγκεκριμένη τιμή είναι μέλος του τύπου απαρίθμησης **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T | Η τιμή που θα ελεγχθεί |

### Τιμή Επιστροφής

Αληθές εάν **value** είναι μέλος της απαρίθμησης **T**, διαφορετικά - ψευδές

## Enum::IsDefined(const String\&) μέθοδος


Καθορίζει εάν η τιμή με το καθορισμένο όνομα βρίσκεται μεταξύ των μελών της απαρίθμησης **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../string/)\& | Το όνομα που θα ελεγχθεί |

### Τιμή Επιστροφής

Αληθές εάν υπάρχει μέλος της απαρίθμησης **E** με το καθορισμένο όνομα.

## Δείτε επίσης

* Typedef [UnderlyingType](../underlyingtype/)
* Κλάση [String](../../string/)
* Δομή [Enum](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)