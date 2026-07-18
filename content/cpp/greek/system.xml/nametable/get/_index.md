---
title: Get()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τη ατομικοποιημένη συμβολοσειρά με την καθορισμένη τιμή.
type: docs
weight: 27
url: /el/system.xml/nametable/get/
---
## NameTable::Get(const String\&) μέθοδος

Επιστρέφει τη ατομικοποιημένη συμβολοσειρά με την καθορισμένη τιμή.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Το όνομα προς εύρεση. |

### Τιμή Επιστροφής

Το αντικείμενο ατομικοποιημένης συμβολοσειράς ή **nullptr** εάν η συμβολοσειρά δεν έχει ήδη ατομικοποιηθεί.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) μέθοδος

Επιστρέφει τη ατομικοποιημένη συμβολοσειρά που περιέχει τους ίδιους χαρακτήρες με το καθορισμένο εύρος χαρακτήρων στον δεδομένο πίνακα.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Ο πίνακας χαρακτήρων που περιέχει το όνομα προς εύρεση. |
| start | **int32_t** | Ο μηδενικής βάσης δείκτης στον πίνακα που καθορίζει τον πρώτο χαρακτήρα του ονόματος. |
| len | **int32_t** | Ο αριθμός των χαρακτήρων στο όνομα. |

### Τιμή Επιστροφής

Η ατομικοποιημένη συμβολοσειρά ή **nullptr** εάν η συμβολοσειρά δεν έχει ήδη ατομικοποιηθεί. Εάν το **len** είναι μηδέν, επιστρέφεται το [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [NameTable](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)