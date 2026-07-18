---
title: Parse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά σε ισοδύναμο DateTimeOffset.
type: docs
weight: 703
url: /el/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) μέθοδος

Μετατρέπει τη συγκεκριμένη string σε ισοδύναμο [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |

### Τιμή Επιστροφής

[DateTimeOffset](../) που είναι ισοδύναμο με το **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος

Μετατρέπει τη συγκεκριμένη string σε αντικείμενο [DateTimeOffset](../) χρησιμοποιώντας τον καθορισμένο format provider και το στυλ μορφοποίησης.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) για μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Παροχέας μορφοποίησης. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Στυλ μορφοποίησης ημερομηνίας και ώρας. |

### Τιμή Επιστροφής

[DateTimeOffset](../) που είναι ισοδύναμο με το **input**.

## Δείτε επίσης

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [DateTimeOffset](../)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)