---
title: TryParse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο 16-bit υπογεγραμμένο ακέραιο.
type: docs
weight: 14
url: /el/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο 16-bit υπογεγραμμένο ακέραιο.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή. |
| result | **int16_t**\& | Η αναφορά σε μεταβλητή 16-bit υπογεγραμμένου ακέραιου όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή Επιστροφής

True αν η μετατροπή επιτύχει, διαφορετικά - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στον ισοδύναμο 16-bit υπογεγραμμένο ακέραιο, χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός τιμών του αριθμού Enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της συμβολοσειράς αναπαράστασης ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **int16_t**\& | Η αναφορά σε μεταβλητή 16-bit υπογεγραμμένου ακέραιου όπου το αποτέλεσμα της μετατροπής τοποθετείται. |

### Τιμή Επιστροφής

True αν η μετατροπή επιτύχει, διαφορετικά - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) μέθοδος

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) μέθοδος

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) μέθοδος

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Int16](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)