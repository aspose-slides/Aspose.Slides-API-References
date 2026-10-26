---
title: TryParse()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο DateTimeOffset.
type: docs
weight: 729
url: /el/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) προς μετατροπή. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) που είναι ισοδύναμο με το **input**. |

### Τιμή Επιστροφής

true εάν η **input** μετατράπηκε επιτυχώς, διαφορετικά - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας το συγκεκριμένο παροχέα μορφής και το στυλ μορφοποίησης.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Παροχέας μορφής. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) που είναι ισοδύναμο με το **input**. |

### Τιμή Επιστροφής

true εάν η **input** μετατράπηκε επιτυχώς, διαφορετικά - false.

## Δείτε επίσης

* Απαρίθμηση [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Ορισμός τύπου [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [DateTimeOffset](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)