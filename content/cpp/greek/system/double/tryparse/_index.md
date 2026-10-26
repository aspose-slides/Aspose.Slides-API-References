---
title: TryParse()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή σημείου κινητής υποδιαστολής διπλής ακρίβειας.
type: docs
weight: 14
url: /el/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή σημείου κινητής υποδιαστολής διπλής ακρίβειας.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| result | **double**\& | Η αναφορά σε μια μεταβλητή σημείου κινητής υποδιαστολής διπλής ακρίβειας όπου το αποτέλεσμα της μετατροπής αποθηκεύεται. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - ψευδές.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή σημείου κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός bitwise τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της αναπαράστασης της συμβολοσειράς ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε ένα αντικείμενο που περιέχει πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **double**\& | Η αναφορά σε μια μεταβλητή σημείου κινητής υποδιαστολής διπλής ακρίβειας όπου το αποτέλεσμα της μετατροπής αποθηκεύεται. |

### Τιμή Επιστροφής

Αληθές εάν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - ψευδές.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) μέθοδος

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) μέθοδος

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) μέθοδος

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)