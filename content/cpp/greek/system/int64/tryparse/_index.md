---
title: TryParse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-bit υπογεγραμμένη ακέραια τιμή.
type: docs
weight: 14
url: /el/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) μέθοδος


Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-ψηφιακή υπογεγραμμένη ακέραια τιμή.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά που θα μετατραπεί. |
| result | **int64_t**\& | Η αναφορά σε μεταβλητή τύπου 64-bit υπογεγραμμένο ακέραιο όπου θα τοποθετηθεί το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε επιτυχώς, διαφορετικά - ψευδές.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) μέθοδος


Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη 64-ψηφιακή υπογεγραμμένη ακέραια τιμή χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά που θα μετατραπεί. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **int64_t**\& | Η αναφορά σε μεταβλητή τύπου 64-bit υπογεγραμμένο ακέραιο όπου θα τοποθετηθεί το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε επιτυχώς, διαφορετικά - ψευδές.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) μέθοδος




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) μέθοδος




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) μέθοδος




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Ορισμός τύπου [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Int64](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)