---
title: TryParse()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας.
type: docs
weight: 14
url: /el/system/single/tryparse/
---
## Single::TryParse(const String&, float&) μέθοδος


Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην αντίστοιχη τιμή κινητής υποδιαστολής μονής ακρίβειας.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)& | Η συμβολοσειρά προς μετατροπή. |
| result | **float**& | Η αναφορά σε μεταβλητή κινητής υποδιαστολής μονής ακρίβειας όπου θα τοποθετηθεί το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - false.

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&, float&) μέθοδος


Μετατρέπει το συγκεκριμένο συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην αντίστοιχη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |
| result | **float**& | Η αναφορά σε μεταβλητή κινητής υποδιαστολής μονής ακρίβειας όπου θα τοποθετηθεί το αποτέλεσμα της μετατροπής. |

### Τιμή Επιστροφής

True αν η μετατροπή ολοκληρώθηκε με επιτυχία, διαφορετικά - false.

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&, float&) μέθοδος




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&, float&) μέθοδος




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, float&) μέθοδος




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Δείτε Επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Δομή [Single](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)