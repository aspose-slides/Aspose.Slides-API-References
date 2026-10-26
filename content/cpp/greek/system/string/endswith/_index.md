---
title: EndsWith()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά.
type: docs
weight: 482
url: /el/system/string/endswith/
---
## String::EndsWith(const String\&) const μέθοδος

Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |

### Τιμή Επιστροφής

true εάν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά, false διαφορετικά.

## String::EndsWith(const String\&, System::StringComparison) const μέθοδος

Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία, δείτε [System::StringComparison](../../stringcomparison/) για λεπτομέρειες. |

### Τιμή Επιστροφής

true εάν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά, false διαφορετικά.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const μέθοδος

Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Συμβολοσειρά αναζήτησης. |
| ignoreCase | **bool** | Καθορίζει εάν η σύγκριση είναι ανεξάρτητη από πεζά-κεφαλαία. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί κατά τη σύγκριση συμβολοσειρών. |

### Τιμή Επιστροφής

true εάν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά, false διαφορετικά.

## Δείτε επίσης

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)