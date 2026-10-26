---
title: ReferenceEquals()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Ειδίκευση του Object::ReferenceEquals για περίπτωση συμβολοσειράς και nullptr."
type: docs
weight: 261
url: /el/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) μέθοδος


Ειδίκευση του [Object::ReferenceEquals](./) για περίπτωση συμβολοσειράς και nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) για σύγκριση με nullptr. |

### Τιμή επιστροφής

true if string is null, false otherwise.

## Object::ReferenceEquals(String const\&, String const\&) μέθοδος


Ειδίκευση του [Object::ReferenceEquals](./) για περίπτωση συμβολοσειρών.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Πρώτη συμβολοσειρά για σύγκριση. |
| str2 | [String](../../string/) const\& | Δεύτερη συμβολοσειρά για σύγκριση. |

### Τιμή επιστροφής

true if strings match, false otherwise.

## Object::ReferenceEquals(ptr const\&, ptr const\&) μέθοδος


Συγκρίνει αντικείμενα κατά αναφορά.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Πρώτος δείκτης για σύγκριση. |
| objB | [ptr](../ptr/) const\& | Δεύτερος δείκτης για σύγκριση. |

### Τιμή επιστροφής

True if pointers match and false otherwise.

## Object::ReferenceEquals(T const\&, T const\&) μέθοδος


Συγκρίνει αντικείμενα κατά αναφορά.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος των αντικειμένων για σύγκριση. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objA | T const\& | Πρώτο αντικείμενο για σύγκριση. |
| objB | T const\& | Δεύτερο αντικείμενο για σύγκριση. |

### Τιμή επιστροφής

True if object addresses match and false otherwise.

## Object::ReferenceEquals(T const\&, std::nullptr_t) μέθοδος


Αναφορά-συγκρίνει αντικείμενο τιμής με nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος του αντικειμένου για σύγκριση. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objA | T const\& | Πρώτο αντικείμενο για σύγκριση. |

### Τιμή επιστροφής

Always returns false as value types cannot be nulled.

## Δείτε επίσης

* Typedef [ptr](../ptr/)
* Κλάση [String](../../string/)
* Κλάση [Object](../)
* Δομή [IsSmartPtr](../../issmartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)