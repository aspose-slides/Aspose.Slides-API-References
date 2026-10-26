---
title: ParseExact()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο TimeSpan χρησιμοποιώντας τις καθορισμένες μορφές, τον πάροχο μορφής και τα στυλ.
type: docs
weight: 547
url: /el/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Μετατρέπει τη συμβολοσειρά σε ισοδύναμο [TimeSpan](../) αντικείμενο χρησιμοποιώντας τις καθορισμένες μορφές, τον πάροχο μορφής και τα στυλ.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Συμβολοσειρά εισόδου. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) των συμβολοσειρών μορφής. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής που παρέχει πληροφορίες μορφοποίησης ειδικές για πολιτισμό. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Καθορίζει τα στοιχεία που μπορεί να υπάρχουν στη συμβολοσειρά εισόδου. |

### Τιμή επιστροφής

Διάστημα χρόνου που αντιστοιχεί στη συμβολοσειρά.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Μετατρέπει τη συμβολοσειρά σε ισοδύναμο [TimeSpan](../) αντικείμενο χρησιμοποιώντας την καθορισμένη μορφή, τον πάροχο μορφής και τα στυλ.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Συμβολοσειρά εισόδου. |
| format | const [String](../../string/)\& | Συμβολοσειρά τυπικής ή προσαρμοσμένης μορφής. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής που παρέχει πληροφορίες μορφοποίησης ειδικές για πολιτισμό. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Καθορίζει τα στοιχεία που μπορεί να υπάρχουν στη συμβολοσειρά εισόδου. |

### Τιμή επιστροφής

Διάστημα χρόνου που αντιστοιχεί στη συμβολοσειρά.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Δείτε επίσης

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)