---
title: TryParseExact()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο DateTimeOffset χρησιμοποιώντας τις καθορισμένες μορφές, τον πάροχο μορφοποίησης και το στυλ μορφοποίησης.
type: docs
weight: 742
url: /el/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας τις καθορισμένες μορφές, τον πάροχο μορφοποίησης και το στυλ μορφοποίησης.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Πίνακες συμβολοσειρών μορφοποίησης. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφοποίησης. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) που είναι ισοδύναμο με το **input**. |

### Τιμή Επιστροφής

αληθές αν το **input** μετατράπηκε επιτυχώς, διαφορετικά - ψευδές.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας τη συγκεκριμένη μορφή, τον πάροχο μορφοποίησης και το στυλ μορφοποίησης.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| format | const [String](../../string/)\& | Συμβολοσειρά μορφοποίησης. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφοποίησης. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) που είναι ισοδύναμο με το **input**. |

### Τιμή Επιστροφής

αληθές αν το **input** μετατράπηκε επιτυχώς, διαφορετικά - ψευδές.

## Δείτε επίσης

* Απαρίθμηση [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Τύπος [ArrayPtr](../../arrayptr/)
* Τύπος [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [DateTimeOffset](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)