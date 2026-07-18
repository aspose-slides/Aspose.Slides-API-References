---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο αντίστοιχο αντικείμενο DateTime.
type: docs
weight: 885
url: /el/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο αντίστοιχο αντικείμενο [DateTime](../).

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας προς μετατροπή. |
| result | [DateTime](../)\& | Το όρισμα εξόδου που, εάν η μετατροπή επιτύχει, περιέχει το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή επιτύχει, διαφορετικά - ψευδές.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο αντίστοιχο αντικείμενο [DateTime](../) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικές για τον πολιτισμό και το στυλ.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει πληροφορίες μορφοποίησης ειδικές για τον πολιτισμό. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Ένας συνδυασμός δυαδικών τιμών του enumeration που παρέχει πρόσθετες πληροφορίες σχετικά με **s**, σχετικά με στοιχεία στυλ που μπορεί να είναι παρόντα στο **s**, ή σχετικά με τη μετατροπή του **s** σε ένα αντικείμενο [DateTime](../). |
| result | [DateTime](../)\& | Το όρισμα εξόδου που, εάν η μετατροπή επιτύχει, περιέχει το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή επιτύχει, διαφορετικά - ψευδές.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) μέθοδος




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) μέθοδος




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) μέθοδος




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Δείτε επίσης

* Απαρίθμηση [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Τύπος [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [DateTime](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)