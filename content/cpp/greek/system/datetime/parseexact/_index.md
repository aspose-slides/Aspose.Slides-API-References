---
title: ParseExact()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στο ισοδύναμο αντικείμενο DateTime χρησιμοποιώντας το καθορισμένο φορμάτ και τις πολιτισμικές πληροφορίες φορμάτ. Το φορμάτ της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο φορμάτ. Εναποκρίνεται εξαίρεση εάν η μετατροπή αποτύχει.
type: docs
weight: 872
url: /el/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στην ισοδύναμη [DateTime](../) αντικείμενο χρησιμοποιώντας το καθορισμένο φορμάτ και τις πολιτισμικές πληροφορίες φορμάτ. Το φορμάτ της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο φορμάτ. Εναποκρίνεται εξαίρεση εάν η μετατροπή αποτύχει.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας για μετατροπή. |
| format | const [String](../../string/)\& | Το φορμάτ της συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το [IFormatProvider](../../iformatprovider/) αντικείμενο που παρέχει πολιτισμικές πληροφορίες φορμάτ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Ένας συνδυασμός δυαδικών τιμών της απαριθμήσιμης τιμής που παρέχει πρόσθετες πληροφορίες σχετικά με **s**, σχετικά με στοιχεία στυλ που ενδέχεται να είναι παρόντα σε **s**, ή σχετικά με τη μετατροπή από **s** σε ένα [DateTime](../) αντικείμενο. |

### Τιμή Επιστροφής

Μια νέα εμφάνιση της [DateTime](../) κλάση που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ισοδύναμη με αυτή που αναπαρίσταται από την καθορισμένη συμβολοσειρά.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) μέθοδος


Μετατρέπει την καθορισμένη αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας στην ισοδύναμη [DateTime](../) αντικείμενο χρησιμοποιώντας τις καθορισμένες φορμάτ, τις πολιτισμικές πληροφορίες φορμάτ και το στυλ. Το φορμάτ της αναπαράστασης συμβολοσειράς πρέπει να ταιριάζει ακριβώς με ένα ή περισσότερα από τα καθορισμένα φορμάτ. Εναποκρίνεται εξαίρεση εάν η μετατροπή αποτύχει.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση συμβολοσειράς μιας τιμής ημερομηνίας και ώρας για μετατροπή. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Ο πίνακας των φορμάτ των συμβολοσειρών. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το [IFormatProvider](../../iformatprovider/) αντικείμενο που παρέχει πολιτισμικές πληροφορίες φορμάτ. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Ένας συνδυασμός δυαδικών τιμών της απαριθμήσιμης τιμής που παρέχει πρόσθετες πληροφορίες σχετικά με **s**, σχετικά με στοιχεία στυλ που ενδέχεται να είναι παρόντα σε **s**, ή σχετικά με τη μετατροπή από **s** σε ένα [DateTime](../) αντικείμενο. |

### Τιμή Επιστροφής

Μια νέα εμφάνιση της [DateTime](../) κλάση που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ισοδύναμη με αυτή που αναπαρίσταται από την καθορισμένη συμβολοσειρά.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) μέθοδος




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Δείτε επίσης

* Απαριθμός [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Ορισμός τύπου [SharedPtr](../../sharedptr/)
* Ορισμός τύπου [ArrayPtr](../../arrayptr/)
* Κλάση [DateTime](../)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)