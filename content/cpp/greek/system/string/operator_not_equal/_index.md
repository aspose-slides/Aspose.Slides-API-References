---
title: operator!=()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Τελεστής σύγκρισης ανισότητας.
type: docs
weight: 313
url: /el/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const μέθοδος


Τελεστής σύγκρισης ανισότητας.

```cpp
bool System::String::operator!=(const String &str) const
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) για σύγκριση με το τρέχον. |

### Τιμή Επιστροφής

false αν και οι δύο συμβολοσειρές είναι null ή και οι δύο δεν είναι null και ταιριάζουν, true διαφορετικά.

## String::operator!=(std::nullptr_t) const μέθοδος


Ελέγχει αν η συμβολοσειρά δεν είναι null. Εφαρμόζει την ίδια λογική με την κλήση [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```


### Τιμή Επιστροφής

false αν η συμβολοσειρά είναι null, true διαφορετικά.

## Δείτε επίσης

* Κλάση [String](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)