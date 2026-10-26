---
title: ToString()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει όλες τις τιμές του καθορισμένου πίνακα byte σε δεκαεξαδική αναπαράσταση κειμένου. Η μορφή των γραμμάτων που θα χρησιμοποιηθεί στη δεκαεξαδική σημειογραφία και ο διαχωριστής που εισάγεται μεταξύ κάθε ζεύγους διαδοχικών bytes καθορίζονται μέσω των αντίστοιχων επιχειρημάτων.
type: docs
weight: 157
url: /el/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) μέθοδος

Μετατρέπει όλες τις τιμές του καθορισμένου byte array σε δεκαεξαδική αναπαράσταση κειμένου. Η περίπτωση των γραμμάτων που θα χρησιμοποιηθούν στην δεκαεξαδική σημειογραφία και ο διαχωριστής που εισάγεται μεταξύ κάθε ζεύγους διαδοχικών bytes καθορίζονται μέσω των αντίστοιχων ορισμάτων.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα bytes για μετατροπή |
| uppercase | **bool** | Καθορίζει τη μορφή των γραμμάτων που θα χρησιμοποιηθούν στην τελική δεκαεξαδική αναπαράσταση |
| separator | const [String](../../string/)\& | Μια συμβολοσειρά που χρησιμοποιείται ως διαχωριστής και εισάγεται μεταξύ κάθε ζεύγους διαδοχικών bytes στην τελική συμβολοσειρά |

### Τιμή Επιστροφής

[String](../../string/) που περιέχει τη δεκαεξαδική αναπαράσταση του καθορισμένου byte array

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) μέθοδος

Μετατρέπει τις τιμές του καθορισμένου byte array σε δεκαεξαδική αναπαράσταση κειμένου ξεκινώντας από το καθορισμένο δείκτη.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον καθορισμένο πίνακα από τον οποίο αρχίζει η μετατροπή |

### Τιμή Επιστροφής

[String](../../string/) που περιέχει τη δεκαεξαδική αναπαράσταση του καθορισμένου εύρους στοιχείων του καθορισμένου πίνακα

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) μέθοδος

Μετατρέπει ένα εύρος τιμών του καθορισμένου byte array σε δεκαεξαδική αναπαράσταση κειμένου.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) που περιέχει τα bytes για μετατροπή |
| startIndex | int | Δείκτης στον καθορισμένο πίνακα από τον οποίο αρχίζει το εύρος των στοιχείων του byte array προς μετατροπή |
| length | int | Το μήκος του εύρους των στοιχείων του byte array προς μετατροπή |

### Τιμή Επιστροφής

[String](../../string/) που περιέχει τη δεκαεξαδική αναπαράσταση του καθορισμένου εύρους στοιχείων του καθορισμένου πίνακα

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [String](../../string/)
* Κλάση [BitConverter](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)