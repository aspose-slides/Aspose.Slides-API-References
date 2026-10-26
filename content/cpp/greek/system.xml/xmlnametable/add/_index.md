---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν αντικαθίσταται σε μια παράγωγη κλάση, ατομικοποιεί τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο XmlNameTable.
type: docs
weight: 14
url: /el/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) μέθοδος


Όταν αντικαθίσταται σε μια παράγωγη κλάση, ατομικοποιεί τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Ο πίνακας χαρακτήρων που περιέχει το όνομα προς προσθήκη. |
| offset | **int32_t** | Δείκτης μηδενικής βάσης στον πίνακα που καθορίζει τον πρώτο χαρακτήρα του ονόματος. |
| length | **int32_t** | Ο αριθμός των χαρακτήρων στο όνομα. |

### Τιμή Επιστροφής

Η νέα ατομικοποιημένη συμβολοσειρά ή η υπάρχουσα, εάν υπάρχει ήδη. Εάν το μήκος είναι μηδέν, [String::Empty](../../../system/string/empty/) επιστρέφεται.

## XmlNameTable::Add(const String\&) μέθοδος


Όταν αντικαθίσταται σε μια παράγωγη κλάση, ατομικοποιεί τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Το όνομα προς προσθήκη. |

### Τιμή Επιστροφής

Η νέα ατομικοποιημένη συμβολοσειρά ή η υπάρχουσα, εάν υπάρχει ήδη.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)