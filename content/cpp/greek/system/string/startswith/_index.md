---
title: StartsWith()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει αν η συμβολοσειρά αρχίζει με την καθορισμένη υποσυμβολοσειρά.
type: docs
weight: 469
url: /el/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Ελέγχει αν η συμβολοσειρά αρχίζει με το καθορισμένο υποσυμβολοσειρά.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |

### Τιμή επιστροφής

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, System::StringComparison) const method

Ελέγχει αν η συμβολοσειρά αρχίζει με το καθορισμένο υποσυμβολοσειρά.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode, see [System::StringComparison](../../stringcomparison/) for details. |

### Τιμή επιστροφής

true if string starts with specified substring, false otherwise.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Ελέγχει αν η συμβολοσειρά αρχίζει με το καθορισμένο υποσυμβολοσειρά.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |
| ignoreCase | **bool** | Καθορίζει αν η σύγκριση δεν διακρίνει πεζά-κεφαλαία. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί κατά τη σύγκριση συμβολοσειρών. |

### Τιμή επιστροφής

true if string starts with specified substring, false otherwise.

## Δείτε επίσης

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)