---
title: Compare()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγκρίνει δύο υποσυμβολοσειρές με λιγότερο, ίσο ή μεγαλύτερο.
type: docs
weight: 820
url: /el/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) μέθοδος

Συγκρίνει δύο υποσυμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| indexA | int | Αρχή της πρώτης υποσυμβολοσειράς. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| indexB | int | Αρχή της δεύτερης υποσυμβολοσειράς. |
| length | int | Αριθμός χαρακτήρων για σύγκριση. |
| ignoreCase | **bool** | Καθορίζει αν η σύγκριση είναι ανεξάρτητη από πεζά/κεφαλαία. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερη, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) μέθοδος

Συγκρίνει δύο υποσυμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| indexA | int | Αρχή της πρώτης υποσυμβολοσειράς. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| indexB | int | Αρχή της δεύτερης υποσυμβολοσειράς. |
| length | int | Αριθμός χαρακτήρων για σύγκριση. |
| ignoreCase | **bool** | Καθορίζει αν η σύγκριση είναι ανεξάρτητη από πεζά/κεφαλαία. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί για τη σύγκριση. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερη, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## String::Compare(const String\&, const String\&, System::StringComparison) μέθοδος

Συγκρίνει δύο συμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερη, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) μέθοδος

Συγκρίνει δύο συμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| indexA | int | Αρχή της πρώτης υποσυμβολοσειράς. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| indexB | int | Αρχή της δεύτερης υποσυμβολοσειράς. |
| length | int | Αριθμός χαρακτήρων για σύγκριση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερη, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## String::Compare(const String\&, const String\&, bool) μέθοδος

Συγκρίνει δύο συμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| ignoreCase | **bool** | Καθορίζει αν η σύγκριση είναι ανεξάρτητη από πεζά/κεφαλαία. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερη, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) μέθοδος

Συγκρίνει δύο συμβολοσειρές.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | Πρώτη συμβολοσειρά για σύγκριση. |
| strB | const [String](../)\& | Δεύτερη συμβολοσειρά για σύγκριση. |
| ignoreCase | **bool** | Καθορίζει αν η σύγκριση είναι ανεξάρτητη από πεζά/κεφαλαία. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί για τη σύγκριση. |

### Τιμή επιστροφής

Αρνητική τιμή αν η πρώτη υποσυμβολοσειρά είναι μικρότερη από τη δεύτερα, μηδέν αν είναι ίσες, θετική τιμή διαφορετικά.

## Δείτε επίσης

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)