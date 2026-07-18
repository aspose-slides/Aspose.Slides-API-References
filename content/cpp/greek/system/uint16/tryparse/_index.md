---
title: TryParse()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχο ακεραίο 16-bit χωρίς πρόσημο.
type: docs
weight: 14
url: /el/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) μέθοδος


Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχο ακεραίο 16-bit χωρίς πρόσημο.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| result | **uint16_t**\& | Η αναφορά σε μεταβλητή ακεραίου 16-bit χωρίς πρόσημο όπου αποθηκεύεται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ήταν επιτυχής, αλλιώς - ψευδές.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) μέθοδος


Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχο ακεραίο 16-bit χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός τιμών του enum NumberStyles που ορίζει το επιτρεπόμενο στυλ της συμβολοσειράς αναπαράστασης ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **uint16_t**\& | Η αναφορά σε μεταβλητή ακεραίου 16-bit χωρίς πρόσημο όπου αποθηκεύεται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ήταν επιτυχής, αλλιώς - ψευδές.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) μέθοδος




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) μέθοδος




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) μέθοδος




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)