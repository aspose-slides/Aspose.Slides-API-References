---
title: TryParseExact()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο ισοδύναμο αντικείμενο DateTime χρησιμοποιώντας το καθορισμένο μορφότυπο, τις πολιτισμικές πληροφορίες μορφότυπου και το στυλ. Η μορφή της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο μορφότυπο.
type: docs
weight: 898
url: /el/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο ισοδύναμο αντικείμενο [DateTime](../) χρησιμοποιώντας το καθορισμένο μορφότυπο, τις πολιτισμικές πληροφορίες μορφότυπου και το στυλ. Η μορφή της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο μορφότυπο.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας για μετατροπή. |
| format | const [String](../../string/)\& | Ο μορφότυπος συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει τις πληροφορίες μορφότυπου ειδικές για τον πολιτισμό. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Μια δυαδική συνδυαστική τιμή των τιμών της αρίθμησης που παρέχει πρόσθετες πληροφορίες σχετικά με το **s**, σχετικά με στοιχεία στυλ που μπορεί να υπάρχουν στο **s**, ή σχετικά με τη μετατροπή από το **s** σε ένα αντικείμενο [DateTime](../). |
| result | [DateTime](../)\& | Το όρισμα εξόδου που, εάν η μετατροπή επιτύχει, περιέχει το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή επιτύχει, διαφορετικά - ψευδές.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο ισοδύναμο αντικείμενο [DateTime](../) χρησιμοποιώντας τις καθορισμένες μορφές, τις πολιτισμικές πληροφορίες μορφότυπου και το στυλ. Η μορφή της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με μία ή περισσότερες από τις καθορισμένες μορφές.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας για μετατροπή. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Ο πίνακας των μορφότυπων συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει τις πληροφορίες μορφότυπου ειδικές για τον πολιτισμό. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Μια δυαδική συνδυαστική τιμή των τιμών της αρίθμησης που παρέχει πρόσθετες πληροφορίες σχετικά με το **s**, σχετικά με στοιχεία στυλ που μπορεί να υπάρχουν στο **s**, ή σχετικά με τη μετατροπή από το **s** σε ένα αντικείμενο [DateTime](../). |
| result | [DateTime](../)\& | Το όρισμα εξόδου που, εάν η μετατροπή επιτύχει, περιέχει το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή επιτύχει, διαφορετικά - ψευδές.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Δείτε επίσης

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)