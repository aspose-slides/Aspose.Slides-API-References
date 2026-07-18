---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο υπογεγραμμένο ακέραιο 32-bit.
type: docs
weight: 14
url: /el/system/int32/tryparse/
---
## Int32::TryParse(const String&, int32_t&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο υπογεγραμμένο ακέραιο 32-bit.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)& | Η συμβολοσειρά για μετατροπή. |
| result | **int32_t**& | Η αναφορά σε μεταβλητή υπογεγραμμένου ακέραιου 32-bit όπου τοποθετείται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True εάν η μετατροπή ολοκληρωθεί με επιτυχία, διαφορετικά - false.

## Int32::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>&, int32_t&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο υπογεγραμμένο ακέραιο 32-bit χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)& | Η συμβολοσειρά για μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ αναπαράστασης του αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Δείκτης προς αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **int32_t**& | Η αναφορά σε μεταβλητή υπογεγραμμένου ακέραιου 32-bit όπου τοποθετείται το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True εάν η μετατροπή ολοκληρωθεί με επιτυχία, διαφορετικά - false.

## Int32::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>&, int32_t&) μέθοδος




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>&, int32_t&) μέθοδος




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, int32_t&) μέθοδος




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Int32](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)