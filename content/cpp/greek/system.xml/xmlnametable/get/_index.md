---
title: Get()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν υλοποιείται σε παράγωγη κλάση, επιστρέφει τη ατομική συμβολοσειρά που περιέχει τους ίδιους χαρακτήρες με το καθορισμένο εύρος χαρακτήρων στον δοθέντα πίνακα.
type: docs
weight: 1
url: /el/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) μέθοδος

When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Ο πίνακας χαρακτήρων που περιέχει το όνομα για αναζήτηση. |
| offset | **int32_t** | Ο μηδενικός δείκτης στον πίνακα που καθορίζει τον πρώτο χαρακτήρα του ονόματος. |
| length | **int32_t** | Ο αριθμός των χαρακτήρων στο όνομα. |

### Τιμή επιστροφής

The atomized string or **nullptr** if the string has not already been atomized. If **length** is zero, [String::Empty](../../../system/string/empty/) is returned.

## XmlNameTable::Get(const String\&) μέθοδος

When overridden in a derived class, gets the atomized string containing the same value as the specified string.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Το όνομα για αναζήτηση. |

### Τιμή επιστροφής

The atomized string or **nullptr** if the string has not already been atomized.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlNameTable](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)