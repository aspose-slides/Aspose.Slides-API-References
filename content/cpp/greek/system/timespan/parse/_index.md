---
title: Parse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο TimeSpan.
type: docs
weight: 534
url: /el/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) μέθοδος


Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](../).

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Συμβολοσειρά εισόδου. |

### Τιμή Επιστροφής

Διάστημα χρόνου που αντιστοιχεί στη συμβολοσειρά.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος


Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](../) χρησιμοποιώντας τον καθορισμένο παροχέα μορφοποίησης.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Συμβολοσειρά εισόδου. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Παροχέας μορφοποίησης που παρέχει πληροφορίες μορφοποίησης ειδικές για πολιτισμό. |

### Τιμή Επιστροφής

Διάστημα χρόνου που αντιστοιχεί στη συμβολοσειρά.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) μέθοδος




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [TimeSpan](../)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)