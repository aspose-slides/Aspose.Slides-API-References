---
title: Add()
second_title: Aspose.Slides για C++ API Reference
description: Ατομιζει τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο NameTable.
type: docs
weight: 14
url: /el/system.xml/nametable/add/
---
## NameTable::Add(const String\&) μέθοδος


Ατομιζει τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Η συμβολοσειρά που θα προστεθεί. |

### Τιμή Επιστροφής

Η ατομιζόμενη συμβολοσειρά ή η υπάρχουσα συμβολοσειρά αν υπάρχει ήδη στο [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) μέθοδος


Ατομιζει τη συγκεκριμένη συμβολοσειρά και την προσθέτει στο [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Ο πίνακας χαρακτήρων που περιέχει τη συμβολοσειρά προς προσθήκη. |
| start | **int32_t** | Ο δείκτης μηδενικής βάσης στον πίνακα που καθορίζει τον πρώτο χαρακτήρα της συμβολοσειράς. |
| len | **int32_t** | Ο αριθμός των χαρακτήρων στη συμβολοσειρά. |

### Τιμή Επιστροφής

Η ατομιζόμενη συμβολοσειρά ή η υπάρχουσα συμβολοσειρά αν υπάρχει ήδη στο [NameTable](../). Αν **len** είναι μηδέν, επιστρέφεται [String::Empty](../../../system/string/empty/).

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [NameTable](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)