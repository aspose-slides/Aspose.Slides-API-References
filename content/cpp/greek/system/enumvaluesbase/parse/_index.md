---
title: Parse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει ένα αντικείμενο που αντιπροσωπεύει την τιμή μιας σταθεράς enum του καθορισμένου τύπου enum με το καθορισμένο όνομα.
type: docs
weight: 27
url: /el/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) μέθοδος

Επιστρέφει ένα αντικείμενο που αντιπροσωπεύει την τιμή μιας σταθεράς enum του καθορισμένου τύπου enum με το καθορισμένο όνομα.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Το αντικείμενο [TypeInfo](../../typeinfo/) που αντιπροσωπεύει τον τύπο της τιμής της απαρίθμησης που θα επιστραφεί |
| str | const [String](../../string/)\& | Το όνομα της σταθεράς enum |
| ignoreCase | **bool** | Καθορίζει εάν η διάκριση πεζών-κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία του ονόματος της σταθεράς enum |

### Τιμή Επιστροφής

Ένα αντικείμενο που αντιπροσωπεύει την τιμή της σταθεράς enum του οποίου το όνομα έχει καθοριστεί στο **str**.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Object](../../object/)
* Κλάση [TypeInfo](../../typeinfo/)
* Κλάση [String](../../string/)
* Κλάση [EnumValuesBase](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)