---
title: TryParse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-bit ακέραια αριθμητική τιμή χωρίς πρόσημο.
type: docs
weight: 14
url: /el/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) μέθοδος


Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-bit ακέραια αριθμητική τιμή χωρίς πρόσημο.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά που θα μετατραπεί. |
| result | **uint64_t**\& | Η αναφορά σε μεταβλητή 64-bit ακέραιου χωρίς πρόσημο όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή επιστροφής

Αληθές εάν η μετατροπή πέτυχε, διαφορετικά - ψευδές.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) μέθοδος


Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-bit ακέραια αριθμητική τιμή χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά που θα μετατραπεί. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας δυαδικός συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της συμβολοσειράς αναπαράστασης αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **uint64_t**\& | Η αναφορά σε μεταβλητή 64-bit ακέραιου χωρίς πρόσημο όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή επιστροφής

Αληθές εάν η μετατροπή πέτυχε, διαφορετικά - ψευδές.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) μέθοδος




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) μέθοδος




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) μέθοδος 




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Δομή [UInt64](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)