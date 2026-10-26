---
title: ToString()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το αντικείμενο.
type: docs
weight: 352
url: /el/system/decimal/tostring/
---
## Decimal::ToString() const μέθοδος

Επιστρέφει την αναπαράσταση σε συμβολοσειρά της τιμής που αντιπροσωπεύεται από το αντικείμενο.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const μέθοδος

Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τις πληροφορίες μορφοποίησης ειδικές για πολιτισμό.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει τις πληροφορίες μορφοποίησης ειδικές για πολιτισμό. |

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const μέθοδος




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const μέθοδος




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const μέθοδός




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const μέθοδος

Μετατρέπει το τρέχον αντικείμενο στην αναπαράσταση του σε συμβολοσειρά χρησιμοποιώντας το συγκεκριμένο φορμά συμβολοσειράς και τις πληροφορίες μορφοποίησης ειδικές για πολιτισμό που παρέχονται από το συγκεκριμένο αντικείμενο [IFormatProvider](../../iformatprovider/).

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../../string/)\& | Το φορμά συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Το αντικείμενο [IFormatProvider](../../iformatprovider/) που παρέχει τις πληροφορίες μορφοποίησης ειδικές για πολιτισμό. |

### Τιμή Επιστροφής

Η αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const μέθοδος




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const μέθοδος




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const μέθοδος




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)