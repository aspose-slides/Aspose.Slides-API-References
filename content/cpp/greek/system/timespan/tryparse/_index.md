---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συμβολοσειρά σε αντίστοιχο αντικείμενο TimeSpan και επιστρέφει το αποτέλεσμα της μετατροπής.
type: docs
weight: 560
url: /el/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) μέθοδος


Μετατρέπει τη συμβολοσειρά σε αντίστοιχο αντικείμενο [TimeSpan](../) και επιστρέφει το αποτέλεσμα της μετατροπής.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Είσοδος συμβολοσειράς. |
| result | [TimeSpan](../)\& | Χρονικό διάστημα που αντιστοιχεί στη συμβολοσειρά. |

### Τιμή Επιστροφής

Αληθής εάν η συμβολοσειρά μετατράπηκε επιτυχώς· διαφορετικά, ψευδής.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) μέθοδος


Μετατρέπει τη συμβολοσειρά σε αντίστοιχο αντικείμενο [TimeSpan](../) χρησιμοποιώντας τον καθορισμένο πάροχο μορφής και επιστρέφει το αποτέλεσμα της μετατροπής.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [String](../../string/)\& | Είσοδος συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφής που παρέχει πληροφορίες μορφοποίησης ειδικές για τον πολιτισμό. |
| result | [TimeSpan](../)\& | Χρονικό διάστημα που αντιστοιχεί στη συμβολοσειρά. |

### Τιμή Επιστροφής

Αληθής εάν η συμβολοσειρά μετατράπηκε επιτυχώς· διαφορετικά, ψευδής.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) μέθοδος




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) μέθοδος




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) μέθοδος




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [TimeSpan](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)