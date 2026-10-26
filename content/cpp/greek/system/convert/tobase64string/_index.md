---
title: ToBase64String()
second_title: Αναφορά API του Aspose.Slides για C++
description: Η Base-64 κωδικοποιεί στοιχεία στον καθορισμένο πίνακα byte και επιστρέφει τα κωδικοποιημένα δεδομένα ως συμβολοσειρά.
type: docs
weight: 40
url: /el/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) μέθοδος

Η Base-64 κωδικοποιεί στοιχεία στον καθορισμένο πίνακα byte και επιστρέφει τα κωδικοποιημένα δεδομένα ως συμβολοσειρά.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes προς κωδικοποίηση |
| insert_line_breaks | **bool** | Καθορίζει αν θα εισαχθούν χαρακτήρες αλλαγής γραμμής στη συμβολοσειρά εξόδου μετά από κάθε 76 χαρακτήρες base-64 |

### Τιμή Επιστροφής

Η συμβολοσειρά που περιέχει την κωδικοποιημένη σε base-64 αναπαράσταση του εισαγόμενου πίνακα

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) μέθοδος

Η Base-64 κωδικοποιεί ένα εύρος στοιχείων στον καθορισμένο πίνακα byte και επιστρέφει τα κωδικοποιημένα δεδομένα ως συμβολοσειρά.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes που περιέχει το εύρος των στοιχείων προς κωδικοποίηση |
| offset_in | int | Δείκτης ενός στοιχείου στον πίνακα εισόδου όπου αρχίζει το εύρος προς κωδικοποίηση |
| length | int | Το μήκος του εύρους των στοιχείων προς κωδικοποίηση |
| insert_line_breaks | **bool** | Καθορίζει αν θα εισαχθούν χαρακτήρες αλλαγής γραμμής στη συμβολοσειρά εξόδου μετά από κάθε 76 χαρακτήρες base-64 |

### Τιμή Επιστροφής

Η συμβολοσειρά που περιέχει την κωδικοποιημένη σε base-64 αναπαράσταση του εύρους των στοιχείων του εισαγόμενου πίνακα

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) μέθοδος

Η Base-64 κωδικοποιεί στοιχεία στον καθορισμένο πίνακα byte και επιστρέφει τα κωδικοποιημένα δεδομένα ως συμβολοσειρά.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes προς κωδικοποίηση |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Καθορίζει τις επιλογές μορφοποίησης των δεδομένων κωδικοποιημένων σε base-64 |

### Τιμή Επιστροφής

Η συμβολοσειρά που περιέχει την κωδικοποιημένη σε base-64 αναπαράσταση του εισαγόμενου πίνακα

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) μέθοδος

Η Base-64 κωδικοποιεί ένα εύρος στοιχείων στον καθορισμένο πίνακα byte και επιστρέφει τα κωδικοποιημένα δεδομένα ως συμβολοσειρά.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ο πίνακας των bytes που περιέχει το εύρος των στοιχείων προς κωδικοποίηση |
| offset_in | int | Δείκτης ενός στοιχείου στον πίνακα εισόδου όπου αρχίζει το εύρος προς κωδικοποίηση |
| length | int | Το μήκος του εύρους των στοιχείων προς κωδικοποίηση |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Καθορίζει τις επιλογές μορφοποίησης των δεδομένων κωδικοποιημένων σε base-64 |

### Τιμή Επιστροφής

Η συμβολοσειρά που περιέχει την κωδικοποιημένη σε base-64 αναπαράσταση του εύρους των στοιχείων του εισαγόμενου πίνακα

## Δείτε επίσης

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)