---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση σε συμβολοσειρά ενός αριθμού στην ισοδύναμη τιμή Decimal.
type: docs
weight: 482
url: /el/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση σε συμβολοσειρά ενός αριθμού στην ισοδύναμη τιμή [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή |
| result | [Decimal](../)\& | Η αναφορά σε μια μεταβλητή [Decimal](../) όπου το αποτέλεσμα της μετατροπής τοποθετείται |

### Τιμή Επιστροφής

Αληθές αν η μετατροπή ολοκληρωθεί επιτυχώς, διαφορετικά - ψευδές

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση σε συμβολοσειρά ενός αριθμού στην ισοδύναμη τιμή [Decimal](../) χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός τιμών του enum NumberStyles με χρήση bitwise που καθορίζει το επιτρεπτό στυλ της συμβολοσειράς που αναπαριστά έναν αριθμό |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε ένα αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς |
| result | [Decimal](../)\& | Μία παράμετρος εξόδου; περιέχει το αποτέλεσμα της μετατροπής |

### Τιμή Επιστροφής

Αληθές αν η μετατροπή ολοκληρωθεί επιτυχώς, διαφορετικά - ψευδές

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Decimal](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)