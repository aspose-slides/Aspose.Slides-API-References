---
title: Equals()
second_title: Aspose.Slides για την αναφορά API C++
description: Σύγκριση ισότητας String. Υποστηρίζονται αρκετές λειτουργίες που παρέχονται από την απαρίθμηση StringComparison.
type: docs
weight: 391
url: /el/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const μέθοδος

[String](../) σύγκριση ισότητας. Υποστηρίζονται αρκετές λειτουργίες που παρέχονται από την απαρίθμηση StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) για σύγκριση με το τρέχον. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία (δείτε [System::StringComparison](../../stringcomparison/) για λεπτομέρειες). |

### Τιμή Επιστροφής

true αν οι συμβολοσειρές ταιριάζουν χρησιμοποιώντας τον επιλεγμένο τύπο σύγκρισης, false διαφορετικά.

## String::Equals(const String\&) const μέθοδος

[String](../) σύγκριση ισότητας. Χρησιμοποιεί τη λειτουργία σύγκρισης [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) για σύγκριση με το τρέχον. |

### Τιμή Επιστροφής

true αν οι συμβολοσειρές ταιριάζουν, false διαφορετικά.

## String::Equals(const String\&, const String\&) μέθοδος

Συγκρίνει ισότητα δύο συμβολοσειρών χρησιμοποιώντας τη λειτουργία σύγκρισης Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |

### Τιμή Επιστροφής

true αν οι συμβολοσειρές ταιριάζουν, false διαφορετικά.

## String::Equals(const String\&, const String\&, System::StringComparison) μέθοδος

Συγκρίνει ισότητα δύο συμβολοσειρών.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή Επιστροφής

true αν οι συμβολοσειρές ταιριάζουν, false διαφορετικά.

## Δείτε επίσης

* Απαρίθμηση [StringComparison](../../stringcomparison/)
* Κλάση [String](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)