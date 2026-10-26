---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 8-bit signed integer.
type: docs
weight: 14
url: /el/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) μέθοδος

Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση της τιμής ενός αριθμού σε ισοδύναμο 8-bit signed integer.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| result | **int8_t**\& | Η αναφορά σε μεταβλητή τύπου 8-bit signed integer όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρωθεί, διαφορετικά - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) μέθοδος

Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση της τιμής ενός αριθμού σε ισοδύναμο 8-bit signed integer χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Μία bitwise συνδυαστική τιμή των τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της συμβολοσειράς αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **int8_t**\& | Η αναφορά σε μεταβλητή τύπου 8-bit signed integer όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρωθεί, διαφορετικά - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) μέθοδος

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) μέθοδος

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) μέθοδος

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Δομή [SByte](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)