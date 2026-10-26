---
title: ToString()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την αναπαράσταση σε συμβολοσειρά της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο, χρησιμοποιώντας τις συμβάσεις μορφοποίησης που ορίζονται από την τρέχουσα πολιτιστική ρύθμιση.
type: docs
weight: 482
url: /el/system/datetime/tostring/
---
## DateTime::ToString() const μέθοδος

Επιστρέφει την αναπαράσταση σε συμβολοσειρά της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τις συμβάσεις μορφοποίησης που ορίζονται από την τρέχουσα πολιτιστική ρύθμιση.

```cpp
String System::DateTime::ToString() const
```

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο

## DateTime::ToString(const String\&) const μέθοδος

Επιστρέφει μια αναπαράσταση σε συμβολοσειρά της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη μορφή και τις συμβάσεις μορφοποίησης που ορίζονται από την τρέχουσα πολιτιστική ρύθμιση.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../../string/)\& | Μία συμβολοσειρά μορφής |

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο μορφοποιημένη σύμφωνα με τη μορφή που ορίζεται από **format** και την τρέχουσα πολιτιστική ρύθμιση.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const μέθοδος

Επιστρέφει μια αναπαράσταση σε συμβολοσειρά της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένα αντικείμενο που αντιπροσωπεύει τις πληροφορίες μορφοποίησης |

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο μορφοποιημένη σύμφωνα με τις πληροφορίες μορφοποίησης που παρέχονται από **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const μέθοδος

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const μέθοδος

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const μέθοδος

```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const μέθοδος

Επιστρέφει μια αναπαράσταση σε συμβολοσειρά της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../../string/)\& | Μία συμβολοσειρά μορφής |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένα αντικείμενο που αντιπροσωπεύει τις πληροφορίες μορφοποίησης |

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο μορφοποιημένη σύμφωνα με τις πληροφορίες μορφοποίησης που παρέχονται από **provider** και τη συμβολοσειρά μορφής **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const μέθοδος

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const μέθοδος

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const μέθοδος

```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)