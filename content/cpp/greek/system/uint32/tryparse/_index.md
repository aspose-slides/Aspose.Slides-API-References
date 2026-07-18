---
title: TryParse()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη δοσμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο.
type: docs
weight: 14
url: /el/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) μέθοδος


Μετατρέπει τη δοσμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχο 32-bit ακέραιο χωρίς πρόσημο.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| result | **uint32_t**\& | Η αναφορά σε μεταβλητή 32-bit ακέραιου χωρίς πρόσημο όπου το αποτέλεσμα της μετατροπής αποθηκεύεται. |

### Τιμή επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - ψευδές.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) μέθοδος


Μετατρέπει τη δοσμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχο 32-bit ακέραιο χωρίς πρόσημο, χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της αναπαράστασης του αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **uint32_t**\& | Η αναφορά σε μεταβλητή 32-bit ακέραιου χωρίς πρόσημο όπου το αποτέλεσμα της μετατροπής αποθηκεύεται. |

### Τιμή επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - ψευδές.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) μέθοδος




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) μέθοδος




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) μέθοδος




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)