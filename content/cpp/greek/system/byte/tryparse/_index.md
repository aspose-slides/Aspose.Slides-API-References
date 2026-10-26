---
title: TryParse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 8-bit μη υπογεγραμμένο ακέραιο.
type: docs
weight: 14
url: /el/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) method

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 8-bit μη υπογεγραμμένο ακέραιο.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Παραμέτρους

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| result | **uint8_t**\& | Η αναφορά σε μεταβλητή 8-bit μη υπογεγραμμένου ακέραιου όπου τοποθετείται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 8-bit μη υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Παραμέτρους

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της συμβολοσειράς αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **uint8_t**\& | Η αναφορά σε μεταβλητή 8-bit μη υπογεγραμμένου ακέραιου όπου τοποθετείται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)