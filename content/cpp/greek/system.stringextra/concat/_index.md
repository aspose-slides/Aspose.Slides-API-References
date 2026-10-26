---
title: Concat()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συνενώνει πίνακα συμβολοσειρών.
type: docs
weight: 1
url: /el/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) συνάρτηση


Συνενώνει έναν πίνακα συμβολοσειρών.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) από συμβολοσειρές για ένωση. |

### Τιμή Επιστροφής

Συνεκτική συμβολοσειρά.

## System::StringExtra::Concat(const String\&, const String\&) συνάρτηση


Συνενώνει συμβολοσειρές.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Πρώτη συμβολοσειρά για ένωση. |
| str1 | const [String](../../system/string/)\& | Δεύτερη συμβολοσειρά για ένωση. |

### Τιμή Επιστροφής

Συνεκτικές συμβολοσειρές παραμέτρων.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) συνάρτηση


Συνενώνει συμβολοσειρές.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Πρώτη συμβολοσειρά για ένωση. |
| str1 | const [String](../../system/string/)\& | Δεύτερη συμβολοσειρά για ένωση. |
| str2 | const [String](../../system/string/)\& | Τρίτη συμβολοσειρά για ένωση. |

### Τιμή Επιστροφής

Συνεκτικές συμβολοσειρές παραμέτρων.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) συνάρτηση


Συνενώνει συμβολοσειρές.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Πρώτη συμβολοσειρά για ένωση. |
| str1 | const [String](../../system/string/)\& | Δεύτερη συμβολοσειρά για ένωση. |
| str2 | const [String](../../system/string/)\& | Τρίτη συμβολοσειρά για ένωση. |
| str3 | const [String](../../system/string/)\& | Τέταρτη συμβολοσειρά για ένωση. |

### Τιμή Επιστροφής

Συνεκτικές συμβολοσειρές παραμέτρων.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) συνάρτηση


Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και ενώνει τις προκύπτουσες συμβολοσειρές. Ειδική υλοποίηση για τύπους [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) για μετατροπή και ένωση. |

### Τιμή Επιστροφής

Τιμή [String](../../system/string/) συγχωνευμένη από τις αναπαραστάσεις συμβολοσειρών όλων των αντικειμένων που περάστηκαν.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) συνάρτηση


Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και ενώνει τις προκύπτουσες συμβολοσειρές. Ειδική υλοποίηση για αριθμητικούς τύπους.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) για μετατροπή και ένωση. |

### Τιμή Επιστροφής

Τιμή [String](../../system/string/) συγχωνευμένη από τις αναπαραστάσεις συμβολοσειρών όλων των αντικειμένων που περάστηκαν.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) συνάρτηση


Μετατρέπει πολλαπλά αντικείμενα σε συμβολοσειρά και ενώνει τις προκύπτουσες συμβολοσειρές. Ειδική υλοποίηση για δομές και άλλους τύπους τιμών.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) για μετατροπή και ένωση. |

### Τιμή Επιστροφής

Τιμή [String](../../system/string/) συγχωνευμένη από τις αναπαραστάσεις συμβολοσειρών όλων των αντικειμένων που περάστηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)