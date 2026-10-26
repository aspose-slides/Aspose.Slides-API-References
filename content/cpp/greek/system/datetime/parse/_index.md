---
title: Parse()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας σε ισοδύναμο αντικείμενο DateTime.
type: docs
weight: 859
url: /el/system/datetime/parse/
---
## DateTime::Parse(const String\&) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας σε ισοδύναμο αντικείμενο [DateTime](../).

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας προς μετατροπή. |

### Τιμή Επιστροφής

Μια νέα παρουσία της κλάσης [DateTime](../) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ισοδύναμη με αυτή που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας σε ισοδύναμο αντικείμενο [DateTime](../) χρησιμοποιώντας πληροφορίες μορφής ειδικές για τον πολιτισμό.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει πληροφορίες μορφής ειδικές για τον πολιτισμό. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Ένας συνδυασμός κατα τμήματα των τιμών της απαρίθμησης που παρέχει πρόσθετες πληροφορίες σχετικά με το **s**, σχετικά με στοιχεία στυλ που μπορεί να υπάρχουν στο **s**, ή σχετικά με τη μετατροπή του **s** σε αντικείμενο [DateTime](../). |

### Τιμή Επιστροφής

Μια νέα παρουσία της κλάσης [DateTime](../) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ισοδύναμη με αυτή που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Δείτε επίσης

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)