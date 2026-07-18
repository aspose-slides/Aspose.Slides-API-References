---
title: ParseExact()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο DateTimeOffset χρησιμοποιώντας τη συγκεκριμένη μορφή, τον πάροχο μορφής και το στυλ μορφοποίησης.
type: docs
weight: 716
url: /el/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας τη συγκεκριμένη μορφή, τον πάροχο μορφής και το στυλ μορφοποίησης.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| format | const [String](../../string/)\& | Συμβολοσειρά μορφής. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |

### Τιμή Επιστροφής

[DateTimeOffset](../) που είναι ισοδύναμο με το **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας τις συγκεκριμένες μορφές, τον πάροχο μορφής και το στυλ μορφοποίησης.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) των συμβολοσειρών μορφής. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |

### Τιμή Επιστροφής

[DateTimeOffset](../) που είναι ισοδύναμο με το **input**.

## Δείτε επίσης

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)