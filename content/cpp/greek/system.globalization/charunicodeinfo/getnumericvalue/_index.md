---
title: GetNumericValue()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει την αριθμητική τιμή που σχετίζεται με τον καθορισμένο χαρακτήρα.
type: docs
weight: 27
url: /el/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) μέθοδος

Επιστρέφει την αριθμητική τιμή που σχετίζεται με τον καθορισμένο χαρακτήρα.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ch | char16_t | Unicode χαρακτήρας. |

### Τιμή Επιστροφής

Η αριθμητική τιμή ή -1 εάν ο καθορισμένος χαρακτήρας δεν είναι αριθμητικός χαρακτήρας.

## CharUnicodeInfo::GetNumericValue(const String\&, int) μέθοδος

Επιστρέφει την αριθμητική τιμή που σχετίζεται με τον χαρακτήρα στη συγκεκριμένη θέση της συμβολοσειράς.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Η συμβολοσειρά που περιέχει τον unicode χαρακτήρα. |
| index | int | Η θέση του unicode χαρακτήρα. |

### Τιμή Επιστροφής

Η αριθμητική τιμή ή -1 εάν ο καθορισμένος χαρακτήρας δεν είναι αριθμητικός χαρακτήρας.

## Δείτε επίσης

* Κατηγορία [CharUnicodeInfo](../)
* Κατηγορία [String](../../../system/string/)
* Χώρος ονομάτων [System::Globalization](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)